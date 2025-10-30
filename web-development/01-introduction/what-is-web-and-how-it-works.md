# How the web works

## 1. What is the Web?

**Web** - short for **World Wide Web**

The **World Wide Web** is a globally interconnected information system that allows computers to **communicate** and **share that information** over the **internet**.

**Web** can be thought of as a giant library where every book is a **webpage**, and links those books together.

> The Web = a network of connected web pages and apps, all accessed through the internet.

## 2. How does the web work?

- **The main components involved in the proper function of the web**

  - > **Clients:** → a user's device + a web browser connected to internet.

  - > **Web server:** → computers that store web pages, sites and apps.

  - > **Internet:** → global network of interconnected computers and cables that allows transmission of information.

  - > **TCP/IP: Transmission Control Protocol** and **Internet Protocol** → unique number of a web page, site or app.

  - > **DNS:** The **Domain Name System** → an address book that contains **TCP/IP** for websites.

  - > **HTTP: Hypertext Transfer Protocol** → a language used between **clients** and **Server** to speak to each other.

  - > **Files:** → codes and assets (imagined as goods that can be bought from a store(**web server**) by a client(**web browser**)).

- **How the components interact concisely**

Let us say we want to visit wikipedia.org homepage

1. Browser(**Client**) asks → **DNS**(address book): “What is the **IP** of wikipedia.org?”
2. **DNS** tells → Browser: “It’s 208.80.154.224.”
3. Browser requests (the homepage with the **IP** through **HTTP/HTTPS** - a communication way between **Client** and **Server**) → Server: “GET /index.html”
4. **Web Server** responds with **Files**(through HTTP/HTTPS again) → Browser: "Here is what you requested" the Files -codes and assets.
5. Browser → using the **Files** displays _Wikipedia homepage_ to the user.

**<u>Note</u> :** all the above interactions done through the **Internet**.
