---
title: "Set personal options (Dynamics 365 Customer Engagement) | MicrosoftDocs"
ms.custom: ""
ms.date: 09/15/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 10711d14-0a84-4b76-b9e9-572ab3113c50
caps.latest.revision: 67
ms.author: "mkaur"
manager: "brycho"
---
# Set personal options

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]

Personalize your [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] Customer Engagement workspace to suit your requirements or preferences. For example, you can choose the page that you want to see as soon as you sign in to [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)]. You can also personalize many other options such as language, currency, and time zone.  
  
<!---   If you’re using [!INCLUDE[pn_crm_for_outlook_full](../includes/pn-crm-for-outlook-full.md)], you can set options that affect synchronization between [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)]. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Set personal options that affect tracking and synchronization between Dynamics 365 and Outlook or Exchange](../admin/set-personal-options-affect-tracking-synchronization-between-dynamics-365-outlook-exchange.md)  
-->  
If you’re an administrator, you can also set system settings that affect all users in the organization. For more information, search for “System Settings dialog box.”  
  
## To set personal options  
  
1.  Click the **Settings** button ![Options button for Dynamics 365](../basics/media/options-button.png "Options button for Dynamics 365") in the upper-right corner of the screen.  
  
2.  Click **Options**.  
  
3.  Fill in the information, as required.  Click on a tab here to see information on settings.  
  
4.  When you’re done, click **OK**.  
  
## General tab options
  
|Options|Description|  
|-------------|-----------------|  
|**Select your home page and settings for Get Started panes**||  
|Default Pane|Select the default home pane (page) that you want to see when you sign in to [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)]. For example, you can make **Service** your default pane if you work mostly in that area.<br /><br /> By default, the **Default based on user role** option is selected, which shows the default pane based on your user role. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [View your user profile](../basics/view-your-user-profile.md)<br /><br /> You can only set panes and tabs that are available for your user role.|  
|Default Tab|Select the default tab that you want to see for the selected default pane. For example, select the **Accounts** tab for the **Services** pane.|  
|**Set the number of records shown per page in any list of records**||  
|Records Per Page|Select the maximum number of records you want to see in a list on a page. You can set a value from 50 to 250.|  
|**Select the default mode in Advanced Find**||  
|Advanced Find Mode|By default, every time you open the **Advanced Find Mode** dialog box, the query details are hidden. To see the query details every time, select **Detailed**. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create, edit, or save an Advanced Find search](../basics/save-advanced-find-search.md)|  
|**Set the time zone you are in**||  
|Time Zone|Select the time zone that you want to display for your region. **Note:**  If you use [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)], set the same time zone in [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] to help prevent a mismatch in dates and times.|  
|**Select a default currency**||  
|Currency|Choose the default currency value to use in financial transactions. Click the **Lookup** button to search for a currency. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Manage transactions with multiple currencies](../admin/manage-transactions-with-multiple-currencies.md)|  
|**Support high contrast settings**||  
|Enable high contrast|Select this check box to enable high contrast levels in your [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] display. **Tip:**  Set this option if you are using high contrast settings in your browser or operating system.|  
|**Set the default country/region code**||  
|Enable country/region code prefixing|Select this check box to enable the default calling code for your region.|  
|Country/Region Code Prefix|Enter the value of your region’s calling code in the text box. For example, enter **+1** for the United States.|  
|View your user information|Select this link to view details about you. These details are displayed to your entire organization and include your contact information and security role. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [View your user profile](../basics/view-your-user-profile.md)|  
  
## Synchronization tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Synchronize [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] items with [!INCLUDE[pn_outlook_short](../includes/pn-outlook-short.md)] or [!INCLUDE[pn_exchange](../includes/pn-exchange.md)]**||  
|filters|Choose the records to synchronize between [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] or [!INCLUDE[pn_exchange](../includes/pn-exchange.md)] (using server-side synchronization). [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Choose the records to synchronize between Dynamics 365 and Outlook or Exchange](../admin/choose-records-synchronize-dynamics-365-outlook-exchange.md)|  
|synchronized fields|View the fields that are synchronized between [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] so you can see where the data is coming from. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)]<br /><br /> -   [View the fields that are synchronized between Dynamics 365 and Dynamics 365 for Outlook](../admin/view-fields-synchronized-dynamics-365-outlook.md)<br />-   [Create or modify synchronization filters or view synchronizing fields](../admin/create-modify-synchronization-filters-view-synchronizing-fields.md) **Note:**  Only a system administrator can change the synchronizing fields.|  
|**Manage your offline filters and take your information offline in [!INCLUDE[pn_crm_outlook](../includes/pn-crm-outlook.md)]**||  
|offline filters|Choose a subset of [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] data that you want to work with when you go offline with [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)]. |  
  
## Activities tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Synchronize [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] items with [!INCLUDE[pn_outlook_short](../includes/pn-outlook-short.md)] or [!INCLUDE[pn_exchange](../includes/pn-exchange.md)]**||  
|filters|Choose the records to synchronize between [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] or [!INCLUDE[pn_exchange](../includes/pn-exchange.md)] (using server-side synchronization). [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Choose the records to synchronize between Dynamics 365 and Outlook or Exchange](../admin/choose-records-synchronize-dynamics-365-outlook-exchange.md)|  
|synchronized fields|View the fields that are synchronized between [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] so you can see where the data is coming from. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)]<br /><br /> -   [View the fields that are synchronized between Dynamics 365 and Dynamics 365 for Outlook](../admin/view-fields-synchronized-dynamics-365-outlook.md)<br />-   [Create or modify synchronization filters or view synchronizing fields](../admin/create-modify-synchronization-filters-view-synchronizing-fields.md) **Note:**  Only a system administrator can change the synchronizing fields.|  
|**Manage your offline filters and take your information offline in [!INCLUDE[pn_crm_outlook](../includes/pn-crm-outlook.md)]**||  
|offline filters|Choose a subset of [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] data that you want to work with when you go offline with [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)]. |  
  
## Formats tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Current Formats**||  
|Format preview|Shows the current region and its formats for **Number**, **Currency**, **Time**, and **Date**.|  
|Customize|Choose this option to add a new region and formats.|  
  
## Email Templates tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Create and modify personal email templates**||  
|New|Create an email template with custom values (such as a date or signature), so you don’t have to enter the same information, repeatedly, when you send an email.<br /><br /> On the command bar, click **New** and enter values for the template. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create templates for email](../admin/create-templates-email.md)|  
  
## Email Signatures tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Create and modify personal email signatures**||  
|New|Create an email signature to save time and be consistent in your responses. The owner of an email signature can be a user or a team.<br /><br /> On the command bar, click **New** and enter values for the signature. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create a signature for your Dynamics 365 email or for a queue](../basics/create-signature-dynamics-365-email-queue.md)|  
  
## Email tab options  
  
|Options|Description|  
|-------------|-----------------|  
|**Select if other users can send emails for you**||  
|Allow other [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] users to send email on your behalf. **Note:**  This option is not available in [!INCLUDE[pn_crm_op_edition](../includes/pn-crm-op-edition.md)].|Select this option to allow other users of [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] to send email on your behalf. **Caution:**  If you select this option, other users can send email on your behalf with or without your consent. Your email name will appear as the sender.|  
|**Select the email messages to track in [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)]**||  
|Track|Select the email messages that you want to  automatically track in [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)].<br /><br /> **Options:**<br /><br /> -   All Email messages<br />-   Email messages in response to [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] email<br />-   Email messages from [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] Leads, Contacts and Accounts<br />-   Email messages from [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] records that are email enabled|  
|Configure Folder Tracking Rules|Set up folders to automatically track incoming email. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Track Outlook email by moving it to a tracked Exchange folder](../admin/track-outlook-email-by-moving-it-tracked-exchange-folder.md)|  
|**Automatically create records in [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)]**||  
|Create|Select this option to allow [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] to create leads or contacts automatically from the information in tracked email messages.|  
|View your Mailbox|Click this link to see your mailbox details.|  
  
## Privacy tab options  
  
> [!NOTE]
>  This tab is available only in [!INCLUDE[pn_CRM_Online](../includes/pn-crm-online.md)]. This tab isn’t available if your system administrator has selected the privacy preference for the entire organization in System Settings. Talk to your administrator. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Find your Dynamics 365 administrator or support person](../basics/find-administrator-support.md)  
  
|Options|Description|  
|-------------|-----------------|  
|**Select your error notification preference**||  
|**Options:**<br /><br /> -   Ask me for permission to send an error report to Microsoft.<br />-   Automatically send report to Microsoft without asking me for permission.<br />-   Never send an error report to Microsoft about [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)].|Specify what you want [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] to do when an error occurs. Based on your selection, the error reports are shared with and used by Microsoft for product improvements. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Set privacy preferences for an organization](../admin/set-privacy-preferences-organization.md)<br /><br /> We recommend that you send the error reports to Microsoft so that Microsoft can use the information for product improvements.|  
  
## Languages tab options    
  
|Options|Description|  
|-------------|-----------------|  
|**Select the language you prefer to see [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] displayed in**||  
|Base Language|Shows the base language. The base language is set during the [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] installation process. You can’t edit this option.|  
|User Interface Language|Select the language that you want to see for labels and dialog boxes in the [!INCLUDE[pn_crm_shortest](../includes/pn-crm-shortest.md)] user interface.|  
|Help Language|Select the language for Help. To add an additional language other than the base language, your admin must install the required language packs and enable them.  Talk to your administrator. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Find your Dynamics 365 administrator or support person](../basics/find-administrator-support.md)|

### See Also
 [Edit your profile](../basics/view-your-user-profile.md)