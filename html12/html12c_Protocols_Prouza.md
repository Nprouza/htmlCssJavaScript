**Before you start:** rename this file to `html12c_Protocols_lastname.md`, using your own last name. Watch videos 7–11 and use **Part 3** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name: Nick Prouza**

---

# Task 12c — Internet Protocols

Type your answers on the blank line under each **Answer:**, or fill in the tables. Explain in your own words where a question asks why.

## 1. Which protocol?

**a.** For each situation, write the protocol that does the job: **HTTP, HTTPS, FTP, SFTP, DNS, TCP, or IP**.

| Situation | Protocol |
|---|---|
| You type `example.com` and your computer needs its IP address | DNS |
| You upload your website's files to a web host | FTP |
| You log in to your bank's website | HTTPS |
| A server sends a plain web page to your browser | HTTP |
| Packet 7 of a file never arrived, so it gets sent again | TCP |
| Each packet needs an address so it reaches the right computer | IP |
| You upload files to a server and want the transfer encrypted | SFTP |

**b.** In your own words, what is a protocol? Give an example from everyday life of two people following the same "rules" so they understand each other.

**Answer:**
Rules for communication. Like two people taking turns talking.

## 2. IP addresses and DNS

**c.** Which of these are valid IPv4 addresses? Write **Valid** or **Not valid**, and give the reason for any that are not.

| Address | Valid? | Reason |
|---|---|---|
| `192.168.0.1` | Valid | Four numbers, each 0–255. |
| `10.0.300.5` | Not valid | `300` is too high. |
| `172.16.4` | Not valid | Only three numbers. |
| `8.8.8.8` | Valid | Four numbers, each 0–255. |

**d.** DNS is called the internet's "phone book." Explain why that comparison makes sense.

**Answer:**
It matches names like `example.com` to IP addresses.

## 3. Packets

**e.** A photo is sent across the internet. It is split into 20 packets, and they take different paths. Packet 12 arrives last and packet 5 never arrives at all. Explain what happens, and which protocol handles it.

**Answer:**
Packets take different routes. Packet 5 is missing, so TCP resends it and reassembles the photo.

## 4. HTTP and HTTPS

**f.** Write the status code for each situation.

| Situation | Status code |
|---|---|
| The page loaded fine | 200 |
| You typed a page name that does not exist | 404 |
| Something broke on the server | 500 |

**g.** A website has a login form but uses `http://` instead of `https://`. What is the risk? What would the browser show?

**Answer:**
Risk: data can be stolen or changed. Browser: “Not secure.”

**h.** What do SSL and TLS have to do with HTTPS? Which one is newer?

**Answer:**
They encrypt the connection. TLS is newer.

## 5. FTP

**i.** What is FTP used for in web design? Why is SFTP a better choice than plain FTP?

**Answer:**
FTP uploads files to a server. SFTP is safer because it encrypts data.

## 6. The parts of a URL

**j.** Break each URL into its parts.

`https://www.medinapets.com/dogs/grooming.html`

| Part | Answer |
|---|---|
| Protocol | `https` |
| Subdomain | `www` |
| Domain name | `medinapets.com` |
| Top-level domain (TLD) | `.com` |
| Path | `/dogs/` |
| File name | `grooming.html` |

`http://library.example.edu/books/index.html`

| Part | Answer |
|---|---|
| Protocol | `http` |
| Subdomain | `library` |
| Domain name | `example.edu` |
| Top-level domain (TLD) | `.edu` |
| Path | `/books/` |
| File name | `index.html` |

**k.** Is the second URL secure? How can you tell?

**Answer:**
No. It uses `http://`, not `https://`.

## 7. Putting it together

**l.** These steps happen when you type a URL and press Enter, but they are out of order. Number them 1–5.

| Order | Step |
|---|---|
| 1 | DNS finds the server's IP address |
| 2 | TCP/IP opens a connection to the server |
| 3 | The browser sends an HTTPS request for the page |
| 4 | The server sends back the HTML, CSS, and images in packets |
| 5 | The browser puts the packets back together and draws the page |

**m.** FTP is not one of those steps. When does FTP get used instead?

**Answer:**
When uploading website files to a host. SFTP is safer.

## Closing 12c — Vocabulary

| Term | Your definition |
|---|---|
| Protocol | Rules for communication. |
| IP address | Device address on a network. |
| DNS | Maps names to IP addresses. |
| Packet | Small chunk of data. |
| HTTPS | Secure HTTP with encryption. |
| URL | Full web address. |
