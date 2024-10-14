type:: [[Artefakt]] 
icon:: 💍
exclude-from-graph-view:: false

- {{query (and (property :type [[Artefakt]]) (not (page [[Templates]])) (not (page [[Artefakt]]))))}}
  query-sort-by:: page
  query-table:: true
  query-sort-desc:: true
  query-properties:: [:icon :page]