things-data-list
-------
获取数据展示到列表

```HTML
<things-data-list
    auto
    has-detail
    id="data-list"
    items-prop="[[itemsProp]]"
    title-field="[[titleField]]"
    info-fields="[[infoFields]]"
    sort-fields="[[sortFields]]"
    data-url="[[dataUrl]]"
    params="[[queryParams]]"
    on-item-selected="_handleItemSelected">
</things-list>
```

things-list
-------
数据展示列表
``` HTML
<things-list
    has-detail
    page="[[page]]"
    items="[[items]]"
    title-field="[[titleField]]"
    info-fields="[[infoFields]]"
    on-next-page="_nextPage"
    on-item-selected="_handleItemSelected">
</things-list>
```