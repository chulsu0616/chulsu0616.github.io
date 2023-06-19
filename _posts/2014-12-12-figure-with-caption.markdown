---
layout: post
title:  "켑션추가"
date:   2023-06-19
---


<p class="intro">이미지 캡션 추가</p>
이미지 캡션 추가 시 figure태그 사용
<figure>
	<img src="/assets/img/songji_lake_sky.jpg" alt=""> 
	<figcaption>Fig1. - 송지호 해변의 하늘</figcaption>
</figure>
소스내용을 표현할 경우 highlight html 사용
{%- highlight html -%}
<figure>
	<img src="/assets/img/songji_lake_sky.jpg" alt=""> 
	<figcaption>Fig1. - This is an example figcaption</figcaption>
</figure>
{%- endhighlight -%}
