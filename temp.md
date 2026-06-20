# Slide Outline — Introduction to Web Development

### From the Internet to Interactive Web Applications

---

# Module Overview

**Audience:** Beginners with little or no web development experience

**Duration:** 3–6 hours (depending on labs)

**Learning Objectives**

By the end of this module, learners should be able to:

* Understand how the web works
* Explain the client-server model
* Describe the roles of HTML, CSS, and JavaScript
* Differentiate frontend and backend development
* Understand browsers and rendering
* Create a simple webpage
* Use browser developer tools
* Prepare for learning modern frameworks like React

---

# Section 1 — Introduction to the Web

---

## Slide 1 — Title

**Introduction to Web Development**

**Subtitle**

How Websites and Web Applications Work

---

## Slide 2 — What Is the Web?

Topics

* The World Wide Web
* Websites vs Web Applications
* Static vs Dynamic Content
* The Web is a distributed information system

Examples

* Wikipedia
* Google Docs
* YouTube
* Amazon

---

## Slide 3 — The Internet vs The Web

Explain the difference.

Internet

* Physical infrastructure
* Networks
* Routers
* TCP/IP

Web

* Built on top of the Internet
* Uses HTTP/HTTPS
* Web pages
* Browsers

Diagram

```
Internet
      │
      ▼
HTTP/HTTPS
      │
      ▼
Web Browser
```

---

## Slide 4 — How the Web Has Evolved

Timeline

* Web 1.0
* Web 2.0
* Mobile Web
* Cloud Computing
* Progressive Web Apps
* AI-powered applications

---

# Section 2 — How the Web Works

---

## Slide 5 — Client–Server Architecture

Introduce:

* Client
* Server
* Request
* Response

Diagram

```
Browser
   │
Request
   │
Server
   │
Response
   │
Browser
```

---

## Slide 6 — What Happens When You Visit a Website?

Step-by-step

1. Enter URL
2. DNS lookup
3. Browser connects to server
4. HTTP request
5. Server processes request
6. HTML returned
7. Browser downloads assets
8. Page rendered

---

## Slide 7 — Anatomy of a URL

Example

```
https://www.example.com/products?id=5
```

Explain

* Protocol
* Domain
* Path
* Query Parameters
* Fragment

---

## Slide 8 — HTTP Request and Response

Topics

Request

* GET
* POST
* PUT
* DELETE

Response

* Status codes
* Headers
* Body

Example

```
GET /index.html HTTP/1.1
```

---

## Slide 9 — Common HTTP Status Codes

Table

* 200 OK
* 201 Created
* 301 Redirect
* 400 Bad Request
* 401 Unauthorized
* 403 Forbidden
* 404 Not Found
* 500 Internal Server Error

---

# Section 3 — Browsers

---

## Slide 10 — What Does a Browser Do?

Responsibilities

* Download files
* Parse HTML
* Parse CSS
* Execute JavaScript
* Render pages
* Manage memory
* Security sandbox

Popular browsers

* Chrome
* Firefox
* Safari
* Edge

---

## Slide 11 — Browser Rendering Pipeline

Diagram

```
HTML
 ↓
DOM

CSS
 ↓
CSSOM

DOM + CSSOM
      ↓
Render Tree
      ↓
Layout
      ↓
Paint
      ↓
Composite
```

---

## Slide 12 — Browser Developer Tools

Introduce

* Elements
* Console
* Network
* Sources
* Performance
* Application

Live demonstration ideas

---

# Section 4 — Core Technologies

---

## Slide 13 — The Three Pillars

Visual

HTML

Structure

CSS

Presentation

JavaScript

Behavior

---

## Slide 14 — HTML

Topics

* Elements
* Tags
* Attributes
* Semantic HTML

Example

```html
<h1>Hello World</h1>
```

---

## Slide 15 — CSS

Topics

* Selectors
* Properties
* Layout
* Colors
* Typography

Example

```css
h1 {
    color: blue;
}
```

---

## Slide 16 — JavaScript

Topics

* Variables
* Functions
* Events
* DOM Manipulation

Example

```javascript
button.onclick = () => {
    alert("Hello");
};
```

---

## Slide 17 — HTML + CSS + JavaScript Together

Diagram

```
HTML
Structure

CSS
Appearance

JavaScript
Interaction
```

Example

Simple webpage with button interaction

---

# Section 5 — Frontend vs Backend

---

## Slide 18 — Frontend Development

Topics

* UI
* Browser
* User Experience
* React
* Angular
* Vue

---

## Slide 19 — Backend Development

Topics

* Business Logic
* Databases
* Authentication
* APIs
* Node.js
* Java
* Python
* .NET

---

## Slide 20 — Full Stack Development

Diagram

```
Browser
     │
Frontend
     │
API
     │
Backend
     │
Database
```

---

# Section 6 — Building Blocks of Modern Web Apps

---

## Slide 21 — APIs

Topics

* What is an API?
* REST
* JSON
* Fetch requests

Example JSON

```json
{
  "name": "Alice",
  "age": 22
}
```

---

## Slide 22 — Databases

Overview

* SQL
* NoSQL

Examples

* PostgreSQL
* MySQL
* MongoDB

---

## Slide 23 — Authentication

Topics

* Login
* Passwords
* Sessions
* Cookies
* JWT

---

## Slide 24 — Hosting a Website

Concepts

* Domain Name
* Web Server
* Hosting
* Cloud

Examples

* GitHub Pages
* Netlify
* Vercel
* AWS

---

# Section 7 — Modern Development Workflow

---

## Slide 25 — Developer Workflow

Flow

```
VS Code

↓

Write Code

↓

Browser

↓

Debug

↓

Git

↓

GitHub

↓

Deploy
```

---

## Slide 26 — Essential Developer Tools

Introduce

* VS Code
* Chrome DevTools
* Git
* GitHub
* Node.js
* npm

---

## Slide 27 — Folder Structure

Example

```
website/

    index.html

    styles.css

    script.js

    images/

    assets/
```

Explain why organization matters.

---

# Section 8 — Hands-on Demo

---

## Slide 28 — Building Your First Webpage

Create

* Heading
* Paragraph
* Button
* Image
* Link

---

## Slide 29 — Adding CSS

Show

* Colors
* Fonts
* Margins
* Borders
* Layout

---

## Slide 30 — Adding JavaScript

Example

* Button click
* Alert
* DOM updates

---

# Section 9 — Looking Ahead

---

## Slide 31 — Challenges of Traditional Web Development

Problems

* Large codebases
* Reusable UI
* State management
* Performance
* Team collaboration

Lead into React.

---

## Slide 32 — Why Frameworks Exist

Discuss

* Reusable components
* Better architecture
* Faster development
* Maintainability
* Ecosystem

Examples

* React
* Angular
* Vue
* Svelte

---

## Slide 33 — Learning Roadmap

```
Internet

↓

HTML

↓

CSS

↓

JavaScript

↓

Git

↓

React

↓

Node.js

↓

APIs

↓

Databases

↓

Full Stack
```

---

## Slide 34 — Summary

Key Takeaways

* The web runs on the client-server model.
* Browsers render HTML, CSS, and JavaScript into interactive experiences.
* HTML provides structure, CSS controls presentation, and JavaScript adds behavior.
* Frontend and backend work together through APIs and HTTP.
* Modern web development relies on version control, developer tools, and deployment platforms.
* Understanding these fundamentals makes learning frameworks like React much easier.

---

# Suggested Hands-on Labs

**Lab 1:** Create Your First HTML Page

* Build a simple personal profile page using semantic HTML elements.

**Lab 2:** Style a Webpage with CSS

* Apply colors, typography, spacing, and layout to improve the page's appearance.

**Lab 3:** Add Interactivity with JavaScript

* Implement button click events, form validation, and dynamic content updates.

**Lab 4:** Explore Browser Developer Tools

* Inspect elements, modify CSS live, monitor network requests, and debug JavaScript.

**Lab 5:** Publish Your Website

* Initialize a Git repository, push the project to GitHub, and deploy it using GitHub Pages or a similar static hosting service.

---

# Recommended Follow-up Modules

1. HTML5 Fundamentals
2. CSS3 and Responsive Design
3. JavaScript Essentials (ES6+)
4. Git & GitHub for Developers
5. React Fundamentals
6. Web APIs and Asynchronous JavaScript
7. Node.js and Express
8. Full-Stack Web Development
