#Office 365 Developer Camp for Education
Andrew Coates

Developer Evangelist

Microsoft Australia

[andrew.coates@microsoft.com](mailto:andrew.coates@microsoft.com)

[@coatsy](https://twitter.com/coatsy)

http://blogs.msdn.com/acoat
##Agenda
###Day 1
| Time  | Module  | Title                         | Notes |
|-------|---------|-------------------------------|-------|
| 09:00 | O3651-1 | [Introduction and Office 365 Developer Overview](https://github.com/OfficeDev/TrainingContent/tree/master/O3651/O3651-1%20Overview%20of%20Office%20365%20Development) |
| 10:00 | O3651-1 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3651/O3651-1%20Overview%20of%20Office%20365%20Development/Lab.md) | 1. The Discover SharePoint app in the lab no longer exists. Try searching for another free app instead. There's a Melbourne Cup sweepstakes app that's quite cool.<br/>2. If you're running Word 2016:<br/>a. The Apps group is now called the Add-ins group, and<br/>b.  the Wikipedia add-in is pre-installed. It's certainly worth enabling it and doing rest of the exercise. Try seaching for another free app as well. There are a couple of cool free Word Cloud apps.<br/>3. You're no longer prompted for the account key by Excel as the Crime dataset now allows unlimited transactions. 
| 10:30 |         | Morning Tea                   |
| 10:45 | O3651-5 | [Getting started with the Office 365 APIs](https://github.com/OfficeDev/TrainingContent/tree/master/O3651/O3651-5%20Getting%20started%20with%20Office%20365%20APIs) |
| 11:30 | O3651-5 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3651/O3651-5%20Getting%20started%20with%20Office%20365%20APIs/Lab.md) | 1. The lab document shows VS 2013. If you're running VS2015 Community Edition, you'll still need to install the Office Developer tools, but the process is slightly different. If you're running VS2015 Professional or above, the Office developer tools should already be installed.<br/>2. VS2015's Add Connected Service wizard is different from what's shown in the lab notes. You should be able to work our what to do though.<br/>3. The wizard will have already added the `TenantId` for you in VS2015, so you don't actually need to go into the Azure Management Portal any more.<br/>4. If you get a `NullReferenceException` in the `SettingsHelper` class, you'll need to change `ida:Password` to `ida:ClientSecret` in that class.<br/>5. You'll want to add a few items into your calendar using the OWA interface so the events show up in this exercise. 
| 12:00 | O3653-1 | [Deep Dive into Azure AD with the Office 365 APIs](https://github.com/OfficeDev/TrainingContent/tree/master/O3653/O3653-1%20Deep%20Dive%20into%20Azure%20AD%20with%20the%20Office%20365%20APIs) |
| 12:45 |         | Lunch |
| 13:30 | O3653-1 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3653/O3653-1%20Deep%20Dive%20into%20Azure%20AD%20with%20the%20Office%20365%20APIs/Lab.md) |
| 14:00 | O3653-8 | [Deep dive into the Office 365 Unified API](https://github.com/OfficeDev/TrainingContent/blob/master/O3653/O3653-8%20Deep%20Dive%20into%20the%20Office%20365%20Unified%20API) |
| 14:45 |         | Afternoon Tea |
| 15:00 | O3653-8 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3653/O3653-8%20Deep%20Dive%20into%20the%20Office%20365%20Unified%20API/Lab.md) |
| 15:30 | O3653-3 | [Deep dive into Office 365 APIs for OneDrive for Business](https://github.com/OfficeDev/TrainingContent/tree/master/O3653/O3653-3%20Deep%20Dive%20into%20Office%20365%20APIs%20for%20OneDrive%20for%20Business) |
| 16:00 |         | Finish |

###Day 2
| Time  | Module  | Title                         |
|-------|---------|-------------------------------|
| 09:00 | O3653-3 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3653/O3653-3%20Deep%20Dive%20into%20Office%20365%20APIs%20for%20OneDrive%20for%20Business/Lab.md) |
| 09:30 | O3657-2 | [Creating Client Side Only Apps with Angular, ADAL and Office 365 API's](https://github.com/OfficeDev/TrainingContent/tree/master/O3657/O3657-2%20Creating%20Client%20Side%20Only%20Apps%20with%20Angular%2C%20ADAL%20and%20Office%20365%20APIs) |
| 10:00 | O3657-2 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3657/O3657-2%20Creating%20Client%20Side%20Only%20Apps%20with%20Angular%2C%20ADAL%20and%20Office%20365%20APIs/Lab.md) |
| 10:30 |         | Morning Tea |
| 10:45 | O3652-7 | [Deep Dive into Security and OAuth](https://github.com/OfficeDev/TrainingContent/tree/master/O3652/O3652-7%20Deep%20Dive%20into%20Security%20and%20OAuth) |
| 11:15 | O3652-7 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3652/O3652-7%20Deep%20Dive%20into%20Security%20and%20OAuth/Lab.md) |
| 11:45 | O3653-9 | [Deep dive into the Office 365 Groups API](https://github.com/OfficeDev/TrainingContent/tree/master/O3653/O3653-9%20Deep%20dive%20into%20the%20Office%20365%20Groups%20API) |
| 12:15 | O3653-9 | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3653/O3653-9%20Deep%20dive%20into%20the%20Office%20365%20Groups%20API/Lab.md) |
| 12:45 |         | Lunch |
| 13:30 | O3652-1 | [Deep Dive into Office Outlook Add-ins](https://github.com/OfficeDev/TrainingContent/tree/master/O3652/O3652-1%20Deep%20Dive%20in%20Office%20Outlook%20Add-ins) |
| 14:15 |         | [Lab](https://github.com/OfficeDev/TrainingContent/blob/master/O3652/O3652-1%20Deep%20Dive%20in%20Office%20Outlook%20Add-ins/Lab.md) |
| 14:45 |         | Afternoon Tea |
| 15:00 | O3652-9 | [Advanced Office Add-ins with Excel, Word, PowerPoint](https://github.com/OfficeDev/TrainingContent/tree/master/O3652/O3652-9%20Advanced%20Office%20Add-ins%20with%20Excel%2C%20Word%2C%20PowerPoint) |
| 15:30 |         | Closing remarks |

##Resources
- Main GitHub Training Content Repository<br/>http://github.com/officedev/trainingcontent 
	- Main GitHub Office Developer Account<br/>http://github.com/officedev
- Landing page for all things Office Developer<br/>http://dev.office.com
- Office Product Team Blogs<br/>http://blogs.office.com
- Office Features Roadmap<br/>http://www.office.com/roadmap
- Office Developer Program (including 1 year O365 developer subscription)<br/>http://dev.office.com/devprogram

