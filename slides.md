---
marp: true
title: Product Documentation using Marp
author: Sirjan Kaur Pahuja
paginate: true
theme: default
---

<!-- Inline Custom Theme -->
<style>
section {
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
}
h1 {
  color: #2d4e8a;
}
h2 {
  color: #333;
}
p {
  line-height: 1.5;
}
code {
  background: #eee;
  padding: 2px 4px;
  border-radius: 4px;
}
</style>

# Product Documentation  
Using Marp for Technical Writing

**Author:** Sirjan Kaur Pahuja  
**Email:** 24f2004829@ds.study.iitm.ac.in

---

# Introduction

Marp enables engineers and technical writers to create  
**maintainable documentation** using Markdown.

- Supports code blocks  
- Supports math equations  
- Works with version control  
- Exports to PDF, PPTX, HTML  

---

![bg](images/bg.jpg)
<!-- _backgroundFit: cover -->
<!-- _color: white -->

# Background Image Example

This slide includes a **full background image**,  
fulfilling the assignment requirement.

---

# Custom Styling With Directives

<!-- _color: #2d4e8a -->
<!-- _class: lead -->

Marp allows **per-slide styling** using directives:

- Change text color  
- Add classes  
- Modify background  
- Add headers/footers  

---

# Code Example

```python
def multiply(a, b):
    return a * b

print(multiply(4, 6))
