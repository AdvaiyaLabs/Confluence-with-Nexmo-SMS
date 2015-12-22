# Confluence with Nexmo SMS
<img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image1.png" width=200>

*“Stay updated of the newly added content or any other updates for your favorite Confluence space and pages via SMS”*

## Introduction

**Confluence with Nexmo SMS** add-on provides extended notification feature in Confluence (for Confluence Hosted on Server or Data Center options). Confluence users can receive notification on their mobile via SMS. Confluence with Nexmo SMS add-on allows to send page created and content updated notifications via SMS to the watchers of the page and space. Confluence administrator can configure Confluence’s spaces, which require SMS notification and also enable and disable the selected events.

## Use case

Build add-on for Confluence to send SMS notifications to all the subscribed users of a specific space whenever any new page is created or an existing page is updated.

For example – when any new knowledgebase article is created in XYZ space, the add-on will send an SMS to all the users who are watchers (Subscribers) of that space.

## Prerequisites 

-   Preinstalled and running on-premise Confluence server

-   Confluence user with administrative privileges

-   Nexmo subscription and corresponding Nexmo API keys (Keys and Secret). To access the Nexmo API keys, see appendix section.

## Features 

-   Sends SMS to page and space watchers.

-   Enable and disable SMS functionality for the Confluence platform.

-   Allow users to enable and disable SMS feature for individual events such as **Page Create** and **Page Update** events.

-   It supports all the custom page templates, but blog post.

## Steps to install the Confluence with Nexmo SMS add-on 

1.  Login with admin user on Confluence server.

2.  Navigate to **Settings**-&gt;**Add-ons** as shown in the image below:

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image2.png">

3.  Click on **Upload add-on** in developer tools section as shown in the screenshot below:

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image3.png">

4.  Click on **Browse** and select the **nexmosms-1.0.jar** file.

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image4.PNg">

5.  Click on **Upload** and the upload process will start.

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image5.png">

6.  On **Installed and ready to go!** screen, click **Close** to continue.

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image6.PNg">

7.  In the list of installed add-ons, newly installed add-on **Confluence with Nexmo SMS** is available.

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image7.PNg">

8.  On Confluence administration screen under the CONFIGURATION section, click on **Nexmo Configuration** option:

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image8.PNg">

9.  On the Nexmo configuration page, provide the following inputs:

    1.  Nexmo Key and Nexmo Secret.

        <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image9.png">

    2.  Click on **Validate.** When the **Nexmo Key** and **Nexmo Secret** validation is done successfully, you will see the remaining additional configuration settings as follows:

        1.  Select **From Number** which is used to send messages. (these are virtual numbers you subscribed from Nexmo).

            <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image10.png">

        2.  Select specific spaces from **All Spaces** list and click on **Add to list** to move it in **Selected Spaces** list.

        3.  Use **Remove** button to remove the unwanted spaces from **Selected Spaces** list.

        4.  To enable SMS feature, ask your users to add phone numbers in their profile along with the country code.

            <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image11.PNg">

10. To enable Confluence with Nexmo SMS feature, select the check box **Enable SMS** and select the check box of respective Page Events (On Page Create and On Page Update).

11. Click on **Save** to complete the add-on installation and save all the settings.

## Steps to use Confluence with Nexmo SMS add-on

Confluence watchers receive an SMS when a new page is created or the content of the page is updated in the configured space.

1.  To enable SMS feature, ask your users to add phone numbers in their profile along with the country code.

2.  Create a new space and select that Space in the **Selected Space** list under Nexmo configuration.

3.  Ask users to watch the configured space.

4.  Click on the space to view its details and click on ***W*atch** to watch the space.

    <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image12.png">

5.  Once users will start watching the configured space, create a new page in the space and save it. Once the page is saved page, space watchers will be notified via SMS.


## Appendix

Nexmo API Keys
------------------------------------------------------------------------------------------------------------

-   To access Nexmo keys, go to <https://www.nexmo.com/> and sign-in

-   On the top right corner, click on the **Api Settings**

-   Key and Secret will display in the top bar as shown in the below image:

> <img src="https://github.com/AdvaiyaLabs/Confluence-with-Nexmo-SMS/blob/master/Docs/image13.png" width=600>
