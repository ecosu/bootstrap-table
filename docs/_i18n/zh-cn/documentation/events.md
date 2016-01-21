# 事件 []({{ site.repo }}/blob/master/docs/_i18n/{{ site.lang }}/documentation/events.md)

---

<table class="table"
       id="e"
       data-search="true"
       data-show-toggle="true"
       data-show-columns="true"
       data-mobile-responsive="true">
    <thead>
    <tr>
        <th>Option 事件</th>
        <th>jQuery 事件</th>
        <th>参数</th>
        <th>描述</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>onAll</td>
        <td>all.bs.table</td>
        <td>name, args</td>
        <td>
        所有的事件都会触发该事件，参数包括：<br>
        name：事件名，<br>
        args：事件的参数。
        </td>
    </tr>
    <tr>
        <td>onClickRow</td>
        <td>click-row.bs.table</td>
        <td>row, $element</td>
        <td>
        当用户点击某一行的时候触发，参数包括：<br>
        row：点击行的数据，<br>
        $element：tr 元素。
        </td>
    </tr>
    <tr>
        <td>onDblClickRow</td>
        <td>dbl-click-row.bs.table</td>
        <td>row, $element</td>
        <td>
        当用户双击某一行的时候触发，参数包括：<br>
        row：点击行的数据，<br>
        $element：tr 元素。
        </td>
    </tr>
    <tr>
        <td>onClickCell</td>
        <td>click-cell.bs.table</td>
        <td>field, value, row, $element</td>
        <td>
        当用户点击某一列的时候触发，参数包括：<br>
        field：点击列的 field 名称，<br>
        value：点击列的 value 值，<br>
        row：点击列的整行数据，<br>
        $element：td 元素。
        </td>
    </tr>
    <tr>
        <td>onDblClickCell</td>
        <td>dbl-click-cell.bs.table</td>
        <td>field, value, row, $element</td>
        <td>
        当用户双击某一列的时候触发，参数包括：<br>
        field：点击列的 field 名称，<br>
        value：点击列的 value 值，<br>
        row：点击列的整行数据，<br>
        $element：td 元素。
        </td>
    </tr>
    <tr>
        <td>onSort</td>
        <td>sort.bs.table</td>
        <td>name, order</td>
        <td>
        当用户对列执行sort排序时候触发，参数包括：<br>
        name：排序的列的filed名称，<br>
        order：排序列的排序方式（asc或者desc）。
        </td>
    </tr>
    <tr>
        <td>onCheck</td>
        <td>check.bs.table</td>
        <td>row</td>
        <td>
        当用户check一行的时候触发，参数包括： <br>
        row: 与点击行关联的记录，<br>
        $element: check的DOM对象。
        </td>
    </tr>
    <tr>
        <td>onUncheck</td>
        <td>uncheck.bs.table</td>
        <td>row</td>
        <td>
        当用户uncheck一行时候触发， 参数包括： <br>
        row: 与点击行关联的记录，<br>
        $element: uncheck的DOM对象。
        </td>
    </tr>
    <tr>
        <td>onCheckAll</td>
        <td>check-all.bs.table</td>
        <td>rows</td>
        <td>
       当用户check所有行的时候触发，参数包括： <br>
        rows: 最新check行关联的记录。
        </td>
    </tr>
    <tr>
        <td>onUncheckAll</td>
        <td>uncheck-all.bs.table</td>
        <td>rows</td>
        <td>
        当用户取消check所有行的时候触发，参数包括: <br>
        rows: 之前check的行关联的数据记录。
        </td>
    </tr>
    <tr>
        <td>onCheckSome</td>
        <td>check-some.bs.table</td>
        <td>rows</td>
        <td>
       当用户check一些行的时候触发，参数包括： <br>
        rows:check行关联的数据记录。
        </td>
    </tr>
    <tr>
        <td>onUncheckSome</td>
        <td>uncheck-some.bs.table</td>
        <td>rows</td>
        <td>
        当用户取消check一些行时候触发，参数包括： <br>
        rows: 取消check行关联的数据记录。
        </td>
    </tr>
    <tr>
        <td>onLoadSuccess</td>
        <td>load-success.bs.table</td>
        <td>data</td>
        <td>远程数据加载成功时候触发。
        </td>
    </tr>
    <tr>
        <td>onLoadError</td>
        <td>load-error.bs.table</td>
        <td>status</td>
        <td>加载远程数据出错时候触发。</td>
    </tr>
    <tr>
        <td>onColumnSwitch</td>
        <td>column-switch.bs.table</td>
        <td>field, checked</td>
        <td>执行切换列的可见性时候触发。</td>
    </tr>
    <tr>
        <td>onColumnSearch</td>
        <td>column-search.bs.table</td>
        <td>field, text</td>
        <td>执行按列查找时候触发。</td>
    </tr>
    <tr>
        <td>onPageChange</td>
        <td>page-change.bs.table</td>
        <td>number, size</td>
        <td>当pagesize或者pagenumber变更时候触发。</td>
    </tr>
    <tr>
        <td>onSearch</td>
        <td>search.bs.table</td>
        <td>text</td>
        <td>执行table的查找时候触发。</td>
    </tr>
    <tr>
        <td>onToggle</td>
        <td>toggle.bs.table</td>
        <td>cardView</td>
        <td>切换table视图（card view）时候触发。</td>
    </tr>
    <tr>
        <td>onPreBody</td>
        <td>pre-body.bs.table</td>
        <td>data</td>
        <td>表格body渲染出来之前触发。</td>
    </tr>
    <tr>
        <td>onPostBody</td>
        <td>post-body.bs.table</td>
        <td>none</td>
        <td>当表格body渲染出来并且在DOM中可用时触发。</td>
    </tr>
    <tr>
       <td>onPostHeader</td>
       <td>post-header.bs.table</td>
       <td>none</td>
       <td>当表格header渲染出来并且在DOM中可用时触发。</td>
    </tr>
    <tr>
        <td>onExpandRow</td>
        <td>expand-row.bs.table</td>
        <td>index, row, $detail</td>
        <td>当点击详细图标展开详细页面的时候触发。</td>
    </tr>
    <tr>
       <td>onCollapseRow</td>
       <td>collapse-row.bs.table</td>
       <td>index, row</td>
       <td>当点击详细图片收起详细页面的时候触发。</td>
    </tr>
    <tr>
       <td>onRefreshOptions</td>
       <td>refresh-options.bs.table</td>
       <td>options</td>
       <td>在刷新options项并且在table初始化完成和销毁之前触发</td>
    </tr>
    </tbody>
</table>
