Date: January 23, 2018

Purpose: Quick example of how to call a CSS static resource in a Lightning Component.  

Uses: -MyApp.app to display the component 
         To display MyApp.app append the following to your Salesforce URL: /c/myapp.app

      -Static Resource: Style with the following settings
		Name	Style
		Description	
		MIME Type	text/css
		Cache Control	Private
		Size	21 bytes
		View file
         CSS code in Style static resource:
			.red {
 				color: red
				}
