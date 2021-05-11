---
layout: post
title:  "HideOuts android app documentation"
date:   2021-05-09 20:00:26 +1000
categories: wasadev
---


`introduction`

HideOuts android app progressive documentations regarding development of its features and functions, user interfaces and other aspects

`your input`

currently HideOuts app is in demo version. it is open to public for trial use. i welcome your feedback and suggestions for considerations as i work towards releasing the final version for upload to Google Play Store. documentations below will provide information about the progressive developments on the app:

   <ul class="post-list">
      {%- for post in site.categories.documentations -%}
      <li>
        {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        <span class="post-meta">{{ post.date | date: date_format }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>



<!--{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %} -->

`special dedication`

HideOuts is dedicated to Nathan, my late team lead at work. what a wonderful father-figure to everyone in the team and the most down-to-earth person we have to know. forever loved and missed!