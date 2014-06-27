---
layout: post
title:  "Glossario"
categories: documento introduzione
---

Questa sezione riporta le definizione di tutti i termini tecnici, acronimi e abbreviazioni utilizzati nel documento.

<table class="table table-bordered">
<tr>
    <th>Termine</th>
    <th>Descrizione</t>
</tr>
{% for termine in site.data.glossario %}
<tr>    
<td>{{ termine.termine }}</td>
<td>{{ termine.descrizione }}</td>
</tr>
{% endfor %}
</table>