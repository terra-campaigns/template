---
layout: default
title: Example PC
parent: party001

hp: 
str: 
dex: 
wil: 

armour: 0

details:
  - ...

image: 

gear:
  - ...

---

{% comment %}
DO NOT EDIT BELOW THIS COMMENT
{% endcomment %}

{% include statblock_pc.md %}

---
#### Connected to
{: .no_toc }

<!-- QueryToSerialize: LIST without ID "["+ title + "](https://terra-campaigns.github.io/" + regexreplace(file.path, ".md", "") + ")" + ", from " + regexreplace(file.folder, "^[^\/]*\/", "") FROM ([[]]) OR outgoing([[]]) WHERE (file.path != this.file.path AND title != null) SORT file.folder DESC -->

{% comment %}
connected_to v0.2
{% endcomment %}
