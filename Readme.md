<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
<!-- default file list end -->
# How to show buttons in a specific column?


<p>To show buttons in cells, you need to use the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraEditorsRepositoryRepositoryItemButtonEdittopic">RepositoryItemButtonEdit</a> as a column's <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridColumnsGridColumn_ColumnEdittopic">ColumnEdit</a>. To hide a text area, please set the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraEditorsRepositoryRepositoryItemButtonEdit_TextEditStyletopic">RepositoryItemButtonEdit.TextEditStyle property</a> to <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraEditorsControlsTextEditStylesEnumtopic">HideTextEditor</a>. To force the GridView to always show buttons in all cells, set the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsBaseColumnView_ShowButtonModetopic">View.ShowButtonMode Property</a> to <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsBaseShowButtonModeEnumEnumtopic">ShowAlways</a></p><p>This example demonstrates this approach in action.</p>

<br/>


