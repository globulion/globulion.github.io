---
title: Methodology
description: Describes methods developed by me
---

I developed the following methods:

<ul>
    {% for method in site.methods %}
        <li>
            <h2>
                <a href="{{ method.url | relative_url }}">
                    {{ method.title }}
                </a>
            </h2>

            <p>
                <i>{{ method.description }}</i>
            </p>
            <p>{{ method.excerpt }}</p>
        </li>
    {% endfor %}
</ul>
