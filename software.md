---
title: About Opencast Software
description: Opencast is an open source solution for automated video capture and distribution at scale. Build custom capture, processing, scheduling and distribution solutions for your organization with one flexible platform.
---
{% include software_menu.html %}

{% include software.html %}

# Latest Releases

{% for post in site.posts limit:3 %}
{% if post.categories contains "release" %}

{% include box-start.html backgroundcolor=site.data.colors.greenbox %}

<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <i>{{ post.date | date_to_long_string }}</i>
  <p>{{ post.description }} <a href="{{ post.url }}">Read more...</a> </p>
  
{% include box-end.html %}
  
{% endif %}
{% endfor %}

---

# [Install Opencast](/install)
Here you will find a test server, installation instructions and the general documenation for Opencast. [Read more...](/install)


# [Features](/features)
What makes Opencast such a great software? Have a look at out feature highlights. [Read more...](/features)


# [Benefits](/benefits)
Additional to the features there are more reasons why Opencast is a reasonable choice for a video management system ant your institution. [Read more...](/benefits)


# [Frequently Asked Questions](/faq)
Here are some frequently asked questions regarding Opencast. This will help you determine if it’s the right solution for your organization. [Read more...](/faq)

---

# See why leading organizations chose Opencast.
Visit our [Users](/users) page in the community section for more report from institutions that use Opencast.
[<img class="center-image" src="/assets/img/opencast-homepage-logos-rev2.png">](/users)
