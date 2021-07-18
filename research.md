---
layout: singlePage
title: "Research"
---

# Research
My ICML Presentation (5 min spotlight talk) on optimal transport for single-cell integration (July 2020):
<div id="presentation-embed-38930906"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38930906', {
        presentationId: '38930906',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

2) My co-first author Berk Alpay's ISMB Proceedings presentation on combinatorial and statistical prediction of gene expression from haplotype sequences (July 2020):
![](https://flash.performedia.com/2020/iscb/ismb2020/pre-recorded-talks/mp4/Berk_Alpay_-_P337_AlpayBerk_VarI.mp4)
<!-- <script>
    embed = new SlidesLiveEmbed('presentation-embed-38930906', {
        presentationId: '38930906',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script> -->




<table class="table table-hover">
  {% for post in site.posts %}
    {% unless post.draft %}
    <tr>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
      <td class="col-md-3" style="text-align: right;">{{ post.date | date: "%B %e, %Y" }}</td>
    </tr>
    {% endunless %}
  {% endfor %}
</table>