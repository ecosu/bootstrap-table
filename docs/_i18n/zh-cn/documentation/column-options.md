# 列参数 []({{ site.repo }}/blob/master/docs/_i18n/{{ site.lang }}/documentation/column-options.md)

---

The column options is defined in `jQuery.fn.bootstrapTable.columnDefaults`.

<table class="table"
       id="c"
       data-search="true"
       data-show-toggle="true"
       data-show-columns="true"
       data-mobile-responsive="true">
    <thead>
    <tr>
        <th>Name</th>
        <th>Attribute</th>
        <th>Type</th>
        <th>Default</th>
        <th>Description</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>radio</td>
        <td>data-radio</td>
        <td>Boolean</td>
        <td>false</td>
        <td>设置为true时显示radio，带有radio的列宽度固定</td>
    </tr>
    <tr>
        <td>checkbox</td>
        <td>data-checkbox</td>
        <td>Boolean</td>
        <td>false</td>
        <td>设置为true时候显示checkbox，带有checkbox的列宽度固定</td>
    </tr>
    <tr>
        <td>field</td>
        <td>data-field</td>
        <td>String</td>
        <td>undefined</td>
        <td>列field属性</td>
    </tr>
    <tr>
        <td>title</td>
        <td>data-title</td>
        <td>String</td>
        <td>undefined</td>
        <td>列标题文本</td>
    </tr>
    <tr>
        <td>titleTooltip</td>
        <td>data-title-tooltip</td>
        <td>String</td>
        <td>undefined</td>
        <td>列标题tooltip文本，该项支持html属性</td>
    </tr>
    <tr>
        <td>class</td>
        <td>class / data-class</td>
        <td>String</td>
        <td>undefined</td>
        <td>列的样式class名称</td>
    </tr>
    <tr>
        <td>rowspan</td>
        <td>rowspan / data-rowspan</td>
        <td>Number</td>
        <td>undefined</td>
        <td>指定一个单元格包含的行数</td>
    </tr>
    <tr>
        <td>colspan</td>
        <td>colspan / data-colspan</td>
        <td>Number</td>
        <td>undefined</td>
        <td>指定一个单元格包含的列数</td>
    </tr>
    <tr>
        <td>align</td>
        <td>data-align</td>
        <td>String</td>
        <td>undefined</td>
        <td>单元格内容水平对齐方式，可用项包括'left', 'right', 'center'</td>
    </tr>
    <tr>
        <td>halign</td>
        <td>data-halign</td>
        <td>String</td>
        <td>undefined</td>
        <td>表格header水平对齐方式，可用项包括'left', 'right', 'center'</td>
    </tr>
    <tr>
        <td>falign</td>
        <td>data-falign</td>
        <td>String</td>
        <td>undefined</td>
        <td>表格footer水平对齐方式，可用项包括'left', 'right', 'center'</td>
    </tr>
    <tr>
        <td>valign</td>
        <td>data-valign</td>
        <td>String</td>
        <td>undefined</td>
        <td>单元格垂直对齐方式，可用想包括 'top', 'middle', 'bottom'</td>
    </tr>
    <tr>
        <td>width</td>
        <td>data-width</td>
        <td>Number {Pixels or Percentage}</td>
        <td>undefined</td>
        <td>列宽度，如果不设置则会根据内容自动调整，可以设置像素或者百分比</td>
    </tr>
    <tr>
        <td>sortable</td>
        <td>data-sortable</td>
        <td>Boolean</td>
        <td>false</td>
        <td>设置为true时可允许列排序
        </td>
    </tr>
    <tr>
        <td>order</td>
        <td>data-order</td>
        <td>String</td>
        <td>'asc'</td>
        <td>默认的排序方式,可以使用'asc'升序或者'desc'降序</td>
    </tr>
    <tr>
        <td>visible</td>
        <td>data-visible</td>
        <td>Boolean</td>
        <td>true</td>
        <td>指定列是否可见</td>
    </tr>
    <tr>
        <td>cardVisible</td>
        <td>data-card-visible</td>
        <td>Boolean</td>
        <td>true</td>
        <td>设置为false时可以使列在卡片视图（card view）隐藏</td>
    </tr>
	<tr>
        <td>switchable</td>
        <td>data-switchable</td>
        <td>Boolean</td>
        <td>true</td>
        <td>指定是否允许切换列显示方式</td>
    </tr>
    <tr>
        <td>clickToSelect</td>
        <td>data-click-to-select</td>
        <td>Boolean</td>
        <td>true</td>
        <td>指定是否允许在点击列的时候勾选checkbox或radio</td>
    </tr>
    <tr>
        <td>formatter</td>
        <td>data-formatter</td>
        <td>Function</td>
        <td>undefined</td>
        <td>
        The context (this) is the column Object. <br>
        The cell formatter function, take three parameters: <br>
        value: the field value. <br>
        row: the row record data.<br>
        index: the row index.</td>
    </tr>
    <tr>
        <td>footerFormatter</td>
        <td>data-footer-formatter</td>
        <td>Function</td>
        <td>undefined</td>
        <td>
        The context (this) is the column Object. <br>
        The function, take one parameter: <br>
        data: Array of all the  data rows. <br>
        the function should return a string with the text to show in the footer cell.
    </tr>
    <tr>
        <td>events</td>
        <td>data-events</td>
        <td>Object</td>
        <td>undefined</td>
        <td>
        The cell events listener when you use formatter function, take three parameters: <br>
        event: the jQuery event. <br>
        value: the field value. <br>
        row: the row record data.<br>
        index: the row index.
        </td>
    </tr>
    <tr>
        <td>sorter</td>
        <td>data-sorter</td>
        <td>Function</td>
        <td>undefined</td>
        <td>
        The custom field sort function that used to do local sorting, take two parameters: <br>
        a: the first field value.<br>
        b: the second field value.
        </td>
    </tr>
    <tr>
        <td>sortName</td>
        <td>data-sort-name</td>
        <td>String</td>
        <td>undefined</td>
        <td>Provide a customizable sort-name, not the default sort-name in the header, or the field name
        of the column. For example, a column might display the value of fieldName of "html" such as  
        "&lt;b&gt;&lt;span style="color:red"&gt;abc&lt;/span&gt;&lt;/b&gt;", but a fieldName to sort is "content" with the value of "abc".
        </td>
    </tr>    
    <tr>
        <td>cellStyle</td>
        <td>data-cell-style</td>
        <td>Function</td>
        <td>undefined</td>
        <td>
        The cell style formatter function, take three parameters: <br>
        value: the field value.<br>
        row: the row record data.<br>
        index: the row index.<br>
        Support classes or css.
        </td>
    </tr>
    <tr>
        <td>searchable</td>
        <td>data-searchable</td>
        <td>Boolean</td>
        <td>true</td>
        <td>
        True to search data for this column.
        </td>
    </tr>
    <tr>
        <td>searchFormatter</td>
        <td>data-search-formatter</td>
        <td>Boolean</td>
        <td>true</td>
        <td>
        True to search use formated data.
        </td>
    </tr>
</tbody>
</table>
