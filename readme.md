## Introduction
*task 1:* create new issues  

*task 2:* setup workflow  

*task 3:* edit readme.md  

*task 4:* run C code  

*task 5:* update web page  

*task 6:* add contributors  

*task 7:* public repo  

## Code
```c
{% include_relative code.c %}
```
![C/C++ CLI Workflow](https://github.com/csci3251-2023/project-team-a/actions/workflows/c-cpp.yml/badge.svg)
## Contributors
<ul>
{% for stu in site.stu %}
  <li>
    <p><img src="{{ stu.image }}" alt="icon" width="50" height="50"> @{{ stu.user }} ({{ stu.name }})</p>
    <ul><li><p>{{ stu.content | markdownify }}</p></li></ul>
  </li>
{% endfor %}
</ul>

Last updated: {{ site.time }}
