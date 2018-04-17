>Make sure to open and check UserSettings.props to fix any broken paths.
>Upgrading from 2012 to 2017 currently causes unknown issues. It's probably linked to a bug which also causes version numbers to misreport.
>Steps to rename this project:
	>Rename Folder
	>Delete .sdf, .suo
	>Rename .sln, .vcproj, .vcxproj, .vcxproj.filters
	>Open .sln with Notepad++, rename near Projects
	>Open exports.def with Notepad++, rename near LIBRARY