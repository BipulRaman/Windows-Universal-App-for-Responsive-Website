# Windows-Universal-App-for-Responsive-Website
A demo app to explain how to convert a responsive website into a Windows10 Universal App.

Step - 1:
Create a Windows Universal App in JavaScript using Visual Studio

Step - 2: 
Remove -- css, js, WinJS, default.html 

Step - 3:
Edit Menifest file (Line 32- 36) as -- 

 StartPage="http://www.bipul.in">

		<uap:ApplicationContentUriRules>
			<uap:Rule Match="http://www.bipul.in" Type="include" WindowsRuntimeAccess="all"/>
		</uap:ApplicationContentUriRules>

Step - 4:
Save, Build, Deploy and Test. 

# License
All files within this repo are released under the [MIT (OSI) License]( https://en.wikipedia.org/wiki/MIT_License) as per the [LICENSE file](./LICENSE) stored in the root of this repo. 
