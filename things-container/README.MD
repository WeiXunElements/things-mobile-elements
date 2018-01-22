things-search-form
-------
根据界面源信息，显示查询界面，再根据输入条件查询数据结果。

```HTML
<things-search-form
    page="{{page}}"
    limit="[[limit]]"
    method="GET"
    content-type="application/json"
    is-object-params
    init-params=[[initParams]]
    form-fields-meta="[[searchFieldsMeta]]"
    search-url="[[searchUrl]]"
    last-response="{{lastResponse}}">
</things-search-form>
```


things-fields-form
-------
根据界面源信息解析的组件数组，显示查询界面，并可触发查询按钮点击事件
``` HTML
<things-fields-form
    form-fields="[[searchFormFields]]"
    sort-fields="[[sortFields]]"
    on-tap-form-btn="_tapFormBtn">
</things-fields-form>
```