<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/DXApplication3/Form1.cs) (VB: [Form1.vb](./VB/DXApplication3/Form1.vb))
* [GroupHelper.cs](./CS/DXApplication3/GroupHelper.cs) (VB: [GroupHelper.vb](./VB/DXApplication3/GroupHelper.vb))
* [Program.cs](./CS/DXApplication3/Program.cs) (VB: [Program.vb](./VB/DXApplication3/Program.vb))
<!-- default file list end -->
# How to display a limited number of child rows in an expanded group in GridView


<p>To limit the number of displayed child rows in expanded groups, create an instance of the GroupHelper class and set its VisibleNumber property to the desired number. Thus, if you expand a group row, the GridView will limit the number of visible child rows by this GroupHelper.VisibleNumber. To show all child rows of a group row, click the "Show all child rows" item in the group row's popup menu. To hide unnecessary child rows again, click the "Show less child rows" popup menu item.</p>

<br/>


