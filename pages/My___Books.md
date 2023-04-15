- #+BEGIN_QUOTE
  ![Avatar512.png](../assets/Avatar512_1681228577135_0.png){:height 24, :width 24}
  Books go into my [[Book]] namespace, this avoids books and movies of the same name clashing, but I also add an alias without the namespace for easy search and reference.  
  #+END_QUOTE
- {{query (page-property :type [[Book]])}}
  query-properties:: [:cover :page :author :updated-at]
-