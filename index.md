---
slug: index
layout: index
title: Hello<span class="hilight">.</span>
intro: Hi 👋🏼 I'm Greg Smith. I'm a UX designer and design system leader with a background in front-end engineering. I build & scale design systems that solve business challenges and improve productivity.
exclude: true
---

{% assign pl_page = site.pages | where: 'slug', 'pattern-libraries' | first %}
{% assign co_page = site.pages | where: 'slug', 'complex-organisms' | first %}
{% assign fp_page = site.pages | where: 'slug', 'figma-plugin' | first %}
{% assign m_page = site.pages | where: 'slug', 'mobile' | first %}
{% comment %}
{% assign dm_page = site.pages | where: 'slug', 'documentation' | first %}
{% assign fx_page = site.pages | where: 'slug', 'flexible-patterns' | first %}
{% endcomment %}
{% assign gv_page = site.pages | where: 'slug', 'governance' | first %}
{%
include work-card.html
image=pl_page.image
alt=pl_page.alt
align=pl_page.align
company=pl_page.company
intro=pl_page.intro
description=pl_page.description
readmore=pl_page.readmore
%}
{%
include work-card.html
image=co_page.image
alt=co_page.alt
align=co_page.align
company=co_page.company
intro=co_page.intro
description=co_page.description
readmore=co_page.readmore
%}
{%
include work-card.html
image=fp_page.image
alt=fp_page.alt
align=fp_page.align
company=fp_page.company
intro=fp_page.intro
description=fp_page.description
readmore=fp_page.readmore
%}
{%
include work-card.html
image=m_page.image
alt=m_page.alt
align=m_page.align
company=m_page.company
intro=m_page.intro
description=m_page.description
readmore=m_page.readmore
%}
{% comment %}
{%
include work-card.html
image=dm_page.image
alt=dm_page.alt
align=dm_page.align
company=dm_page.company
intro=dm_page.intro
description=dm_page.description
readmore=dm_page.readmore
%}
{%
include work-card.html
image=fx_page.image
alt=fx_page.alt
align=fx_page.align
company=fx_page.company
intro=fx_page.intro
description=fx_page.description
readmore=fx_page.readmore
%}
{% endcomment %}
{%
include work-card.html
image=gv_page.image
alt=gv_page.alt
align=gv_page.align
company=gv_page.company
intro=gv_page.intro
description=gv_page.description
readmore=gv_page.readmore
%}
