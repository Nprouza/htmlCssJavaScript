**Before you start:** rename this file to `html12b_SEO_lastname.md`, using your own last name. Watch videos 4–6 and use **Part 2** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name: Nick Prouza**

---

# Task 12b — Search Engine Optimization (SEO)

Type your answers on the blank line under each **Answer:**, or fix the code inside the code boxes. Explain in your own words where a question asks why.

## 1. How a search engine works

**a.** Put the three steps a search engine uses in order, and describe each one in one sentence of your own.

| Step | Name | What happens |
|---|---|---|
| 1 |Crawling |Bots follow links across the web to iscover pages. |
| 2 |Indexing |The engine saves and categorizes the page data. |
| 3 |Ranking |Algorithms order indexed pages to answer user searches. |

**b.** You just built a new page, but **no other page links to it**. Why might a search engine have trouble finding it? (Hint: think about how crawlers find pages.)

**Answer:Crawlers find new pages by following links from existing ones, so with no incoming links, there is no path to discover it.**


## 2. Organic vs. paid

**c.** You search for "pizza Medina Ohio." The first two results say **Sponsored**. The next ones do not. Which results are organic and which are paid? Which kind can SEO help with?

**Answer:** The first two results are paid because they are labeled Sponsored. The results below them are organic. SEO helps improve organic results.

**d.** A business owner asks, "Why would I spend time on SEO when I could just pay for ads?" Give one reason SEO is still worth it.

**Answer:** SEO is worth it because organic rankings can keep bringing traffic over time without paying for every click, so it gives long-term visibility and trust.


## 3. Fix the head

This is the `<head>` of a bakery's home page. It works, but it is weak for SEO.

```html
<head>
  <meta charset="UTF-8">
  <title>Home</title>
</head>
```

**e.** Rewrite it below. Add a strong `<title>`, a meta description, and the viewport meta tag. Make up a name and town for the bakery.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Maple & Crumb Bakery in Medina, Ohio, serves fresh artisan bread, pastries, and custom cakes made with local ingredients.">
  <title>Maple & Crumb Bakery | Fresh Bread, Pastries & Cakes in Medina, OH</title>
</head>
```

**f.** Where does the text in your `<title>` show up? Where does the meta description usually show up?

**Answer:** The text in the `<title>` shows up in the browser tab and is often the main clickable headline in search results. The meta description usually shows up as the short summary under the page title in search engine results.


## 4. Fix the page

**g.** Rewrite this code to be better for SEO and accessibility. Fix the alt text, the link text, and the file name.

```html
<img src="IMG_4471.jpg" alt="picture">
<a href="page3.html">Click here</a> to see our menu.
```

Your fixed version:

```html
<img src="bakery-counter.jpg" alt="Fresh pastries and breads on display at Maple & Crumb Bakery">
<a href="menu.html">View our menu</a>
```

**h.** A page has three `<h1>` tags: one for the logo, one for the page title, and one for the footer. What is wrong, and how should the headings be set up?

**Answer:** There should be only one main `<h1>` on the page, because it represents the primary topic of the page. The logo is not the page heading, so it should be plain text or styled text in the header; the page title should be the single `<h1>`; and any footer heading should be a lower level like `<h2>` or `<h3>` if it needs a heading at all.


## 5. Spot the problem

**i.** Here is a meta description someone wrote:

`content="cheap shoes cheap shoes best cheap shoes buy cheap shoes cheap shoes near me"`

What is this called? What will a search engine do about it? Rewrite it as a good description.

**Answer:** This is called keyword stuffing. A search engine will likely ignore the repeated keywords or reduce the page's value because it looks spammy and not helpful to users. A better meta description is: `content="Shop affordable, comfortable shoes for everyday wear, running, and walking. Find stylish sneakers and casual shoes near you."`

**j.** Name **two** SEO choices that also help people who use screen readers. Explain how each one helps both.

**Answer:** Two good examples are descriptive alt text and clear heading/link text. Descriptive alt text helps search engines understand the image's purpose and gives screen-reader users a useful description of what the image shows. Clear, meaningful heading and link text helps search engines understand page structure and helps screen-reader users navigate the page more easily because they can hear what each section or link is about.


## 6. Your own site

**k.** Write a `<title>` and a meta description for the `index.html` of your DIY website. Then add them to your real `index.html` and push it.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- SEO Tags -->
  <title>DIY Projects &amp; Step-by-Step Craft Guides | [Your Site Name]</title>
  <meta name="description" content="Discover simple, creative DIY projects, step-by-step crafting tutorials, and practical home repair guides to spark your creativity and build it yourself.">

  <!-- Your existing styles or scripts -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Your content -->
</body>
</html>

```


## Closing 12b — Vocabulary

| Term | Your definition |
|---|---|
| SEO | Search Engine Optimization, the practice of improving a website so it ranks higher in search engine results and is easier for users to find. |
| Crawler (spider) | A bot used by search engines to visit web pages, follow links, and gather information for indexing. |
| Organic results | Search results that appear naturally based on relevance and ranking, not paid advertisements. |
| Meta description | A short summary in the HTML head tag that tells search engines and users what a page is about. |
| Keyword stuffing | Overloading a page or meta description with repeated keywords in a way that looks spammy and hurts credibility. |
| SERP | Search Engine Results Page, the page that shows the results after a user searches online. |
