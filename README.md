- 참고 사이트
> https://wlqmffl0102.github.io/posts/Making-Git-blogs-for-beginners-1/
> https://wlqmffl0102.github.io/posts/Making-Git-blogs-for-beginners-2/
> https://olvimama.github.io/blog/gitpages-about-so-simple-theme
> https://github.com/mmistakes/so-simple-theme


- 마크다운 문서 작성시 참고할 내용
> https://github.com/olvimama/olvimama.github.io/tree/master/_posts

- font change 
> check _sass / so-simple / _variables.scss file
> font from https://fonts.google.com/specimen/Nanum+Gothic?lang=ko_Kore

- description 항목 추가 for auther
> includes / page-author.html
"""html
    {%- if author.description -%}
    <div class="author-name">
      <span class="p-name">{{ author.description }}**</span>
    </div>
    {%- endif -%}
"""