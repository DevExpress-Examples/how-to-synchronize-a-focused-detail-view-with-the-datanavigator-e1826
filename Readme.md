<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Q235715/Form1.cs) (VB: [Form1.vb](./VB/Q235715/Form1.vb))
<!-- default file list end -->
# How to synchronize a focused detail view with the DataNavigator


<p>The GridView binds its detail views to a separate collection, that isn't linked with the GridControl's data source. In the situation, when you need to synchronize a focused row of the active detail view with the DataNavigator's position, you can implement this by handling the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraGridViewsBaseColumnView_FocusedRowChangedtopic">GridView.FocusedRowChanged</a> and <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraEditorsDataNavigator_PositionChangedtopic">DataNavigator.PositionChanged</a> events.</p>

<br/>


