# Scratch Coding Practice 101  
## Project 7 of 10 — Embedding Content with iframe (freeCodeCamp)

**Live Project:** [https://sharmaankita3387.github.io/fccHTMLWebsitePractice07/](https://sharmaankita3387.github.io/fccHTMLWebsitePractice07/)  

---

## About This Project  
This is Project 7 in my coding practice series. In this project, I explored the HTML `<iframe>` element to embed external content into a webpage.

The focus was not just on displaying a video, but on understanding how iframes handle **permissions, security policies, and cross-origin content**.

---

## Guiding Principle
> "To become a reliable VibeCoder, you must first understand what’s happening behind the scenes as a Software Engineer."

---

## Key Concepts Practiced
- Embedding external content using the `<iframe>` element  
- Understanding iframe attributes like `allow`, `allowfullscreen`, and `referrerpolicy`  
- Working with embedded media from external platforms (YouTube)  
- Introduction to cross-origin and security considerations  

---

## Why This Project Matters
Embedding external content is a common real-world requirement. This project introduces the balance between functionality and security when integrating third-party resources.

---

## Code Example
```html
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/I0_951_MPE0"
  allow="accelerometer autoplay clipboard-write encrypted-media gyroscope web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen>
</iframe>
