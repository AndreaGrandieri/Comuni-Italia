---
# Front matter of "classic" page

# Theme to use. Resides in the "_layouts" folder.
layout: default

# Page title. If omitted, the page will not be included in the navbar.
title: Comuni-Italia

#################################################################

# Specifies the order of the current page from the point of view of the navbar. Can have repetition in the numbers, for parent-child hierarchies.
nav_order: 1

# Let exclude the page from the navbar
nav_exclude: false

# Let exclude the page from the built-in search engine
search_exclude: false

#################################################################

# Set "true" if this page has childrens, "false" otherwise.
has_children: false

# If this page is some page's child, specify the parent's name, otherwise comment out the option. If this page is some page's grandchild, specify grandparent's name, otherwise comment out the option.
# # parent: NOME_PAGINA_GENITORE
# # grand_parent: NOME_PAGINA_NONNO__GENITORE_DEL_GENITORE

# If this page is a parent page, a Table Of Contents will be automatically generated containing all related child pages. Use the option below to disable this functionality. Should always be set to "false".
has_toc: false

#################################################################

# Specify the current language of this page
lang: it

# Specify all other available languages in which this page is available. If there's no other language in addition to "lang", comment out this option.
# # availableLanguages:
# #   - 

# Notice: codeblocks highlighting supported languages listed here: https://www.fabriziomusacchio.com/blog/2021-08-11-Syntax_Highlighting_in_Jekyll/
---

# Comuni-Italia
{: .no_toc }
{: .d-inline-block }

<div id="projects-label-1"></div>
{: .d-inline-block }

<script type="module">
  selfsustainable_fill_labels_state("projects-label-1");
</script>

<div id="projects-label-2"></div>

<script type="module">
  selfsustainable_fill_labels_state("projects-label-2");
</script>

---

<!-- Table of contents -->
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

{: .motto-title }
> <p class="blockquote-title-fixer-purple">tl;dr</p>
>
> XML e JSON interrogabili via HTTP GET da qualsiasi applicazione per ottenere una completa lista dei comuni italiani.

---

## Autori

- Andrea Grandieri [https://github.com/AndreaGrandieri](https://github.com/AndreaGrandieri)

---

## Uso

Semplicemente interroga via __HTTP GET__ uno dei seguenti link:

  - `XML`: [https://raw.githubusercontent.com/AndreaGrandieri/Comuni-Italia/main/comuni.xml](https://raw.githubusercontent.com/AndreaGrandieri/Comuni-Italia/main/comuni.xml)
  - `JSON`: [https://raw.githubusercontent.com/AndreaGrandieri/Comuni-Italia/main/comuni.json](https://raw.githubusercontent.com/AndreaGrandieri/Comuni-Italia/main/comuni.json)

In alternativa, visita la repository [https://github.com/AndreaGrandieri/Comuni-Italia](https://github.com/AndreaGrandieri/Comuni-Italia) e __scarica__ direttamente gli assets, per poterli usare anche __offline!__
