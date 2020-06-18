<div class="project_list">
  <h2 class="heading center">Projects and Experiments:</h2>
  {% for project in site.data.projects %}
    {% include project_box.html %}
  {% endfor %}
</div>
