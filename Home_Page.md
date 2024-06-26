# Home Page

![Home Page](Images/Home/HomePage.png)

The Safeguard Cyber home page gives the user an overview of all potential threats being monitored within their organization. This page give detailed graphs of set policy indicators, potential malware recipients, people of interest, recent messages and alerts, and shows current activity within the organization.

## Policy Indicators 

The policy indicators widget shows a graph of potential threats marked by the active policies within the organization. In the top left corner of the policy indicators widget you can show indicators by date or by channel.

![Home Page - Policy Indicators](Images/Home/HomePagePolicyIndicators.png)
*Policy Indicators filtered by Date*

![Home Page - Policies Indicators by Channel](Images/Home/HomePagePolicyIndicatorsbyChannel.png)
*Policy Indicators filtered by Channel*

The Policy Indicators widget calculates the total count of results that contain at least one hit per policy type, categorized by date or channel type. The [Archiving/Compliance Policy](Policies_Page.md) operates on customer-selected keywords or phrases for detection. The [Business Compromise Policy](Policies_Page.md) and [Insider Threat Policy](Policies_Page.md) rely on machine learning (ML) results, with their key assigned based on the type and severity of detected actions. 

Currently, the widget displays counts for all policy types, whether the customer has them activated/enabled. This allows customers to observe the total number of captures, regardless of their ability to view the details of those captures. 

## Potential Malware Recipients

The Potential Malware Recipients widget shows organization users that may have recently received a malware threat. Hovering over a name, will show the number of threats the organization user may have received. Clicking on a hovered name will navigate the user to the [Alerts Page](Alerts_Page.md) where they can explore the potential threat further. 

![Home Page - Malware Recipients](Images/Home/HomePageMalwareRecipients.png)
*Potential Malware Recipients Widget*

![Home Page - Malware Recipients Hovered](Images/Home/HomePageMalwareRecipientsHovered.png)
*Potential Malware Recipients with an organization user hovered*

## Daily Messages

The Daily Messages widget shows message sent by organization users. Hovering over a name highlights the organization user's messages on the graph. Selecting the organization user's name will navigate the user to the [Archive Page](Archive_Page.md) where they can explore the data deeper. 

![Home Page - Daily Messages](Images/Home/HomePageDailyMessages.png)
*Daily Messages Widget*

![Home Page - Daily Messages Hovered](Images/Home/HomePageDailyMessagesHovered.png)
*Daily Messages widget with an organization user hovered*

## People of Interest

The People of Interest widget highlights organization users that are not in compliance with the organizations tracked policies. This widget shows shows each user and the count of each policy that they are in non-compliance of. Selecting one of the policies will navigate the user to the [Alerts Page](Alerts_Page.md) where they can view the potential threats in greater detail. 

![Home Page - People of Interest](Images/Home/HomePagePeopleOfInterest.png)
*People of Interest Widget*

## Channel Messages

The Channel Messages widget shows messages from all channels. This gives the user a fast way of viewing the most recent messages withing their organization. 

![Home Page - Channel Messages](Images/Home/HomePageChannelMessages.png)
*Channel Messages Widget*