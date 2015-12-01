While working on an Outlook 2016-related issue, [I found that there is not a straightforward way to set Microsoft Outlook 2016 as the default application for email, contacts and calendars​](https://support.microsoft.com/kb/3027171) . To redress this, I have developed an Automator application named **Set Microsoft Outlook as default application for email calendars and contacts.app** to handle this task.

**Set Microsoft Outlook as default application for email calendars and contacts.app** leverages [duti](http://duti.org), an open source tool used for managing application ownership of document types and URL schemes on Mac OS X, to set the newest version of Microsoft Outlook on the Mac as the default application for email, contacts and calendars. 

The  application includes an embedded copy of duti, so it is not necessary to have duti pre-installed on the Mac in order to use this tool.

###**System requirements**

**Set Microsoft Outlook as default application for email calendars and contacts.app** has been tested and verified to run on the following versions of OS X:

10.9.x

10.10.x

10.11.x

**Set Microsoft Outlook as default application for email calendars and contacts.app** has been tested and verified that it does not run on the following versions of OS X:

10.8.x

10.7.x

**Not tested**:

10.6.x or earlier


### **Using the application**

1. Download a copy of the application from the link below.

2. Unzip the application

3. Double-click on **Set Microsoft Outlook as default application for email calendars and contacts.app**

4. When prompted, click the **OK** or **Cancel** button:

		Clicking the OK button: 
		
			This will set the newest version of Outlook on the Mac as the default application for email, contacts and calendars
		
		Clicking the Cancel button: 
		
			This will exit the application without making changes to the existing email, contacts or calendar settings.


5. If the **OK** button is clicked, the application will make changes to the email, contacts or calendar settings on the Mac to set Outlook as the default application for email, contacts and calendars. 

6. Once the settings changes have been made, the application will notify you that Outlook has been set as the default application for email, contacts and calendars.

7. Click the **Done** button to exit the application.