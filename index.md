---
layout: home
---
<p>
    Hi! My name is Mees-Merijn and I am an International Business Student, specialized in (digital) marketing. I am always up for a challenge (and a drink 😉).
    <br><br>
    I have experience within big companies, such as Postcode Lottery, Shell and Bux, as well as start-ups like Productpine.
    <br><br>
    Experienced in:
    <br>
</p>
<ul>
    {% for item in site.data.experience.entries %}
    <li>{{ item.text }}</li>
    {% endfor %}
</ul>