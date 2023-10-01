---
layout: default
title: Home
---

# Welcome to the TEG Knowledge Base

<!-- This knowledge base contains a collection of insights, tutorials, and documentation to help you understand [your subject/topic]. -->
For now this knowledge base does not include that much...

## Learnings

{% for learning in site.learnings %}
- [{{ learning.title }}]({{ learning.url }})
{{ learning.content | truncatewords: 50 }}
{% endfor %}

<!-- 
## Getting Started

If you're new here, we recommend starting with:

- [Introduction to Topic](#) *(replace with your actual link)*
- [Frequently Asked Questions](#) *(replace with your actual link)*

## Need Help?

For additional assistance or to ask questions, [contact us](/contact) or check out the [about page](/about) to learn more about this project.

---

For the latest updates, consider following [our Twitter](https://twitter.com/yourTwitterHandle) *(update with your actual Twitter handle or remove if not applicable)*. -->