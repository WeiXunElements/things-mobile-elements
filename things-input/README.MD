things-search-form
-------
根据界面源信息，显示查询界面，再根据输入条件查询数据结果。

```HTML
<things-combo-box 
    resource-type="ENTITY"
    resource-ref="Operation" 
    label="[[label]]"
    name="name"
    query-params="[[queryParams]]"
    select-fields="[[selectFields]]"
    label-path="[[labelPath]]"
    value-path="[[valuePath]]"
    value="{{operationId}}"
    filter="[[filter]]">
</things-combo-box>
```

things-fields-form
-------
根据界面源信息解析的组件数组，显示查询界面，并可触发查询按钮点击事件
``` HTML
<things-textfield 
    name="name" 
    type="text" 
    placeholder="[[t('term.placeholder')]]" 
    value="{{value}}" 
    icon="[[icon]]"
    pattern="[[pattern]]" 
    error-message="[[errorMessage]]" 
    required 
    auto-validate 
    autofocus
    readonly="[[readonly]]">
</things-textfield>
```