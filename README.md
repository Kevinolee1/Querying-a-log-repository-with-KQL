# Querying-a-log-repository-with-KQL
is the process of searching, filtering, analyzing, and visualizing log data stored in a centralized log repository. KQL is commonly used in Microsoft Azure Monitor, Microsoft Sentinel, Azure Data Explorer, and Microsoft Defender to efficiently retrieve and investigate large volumes of log data.
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/main/Querying/Screenshot%202026-07-03%20030432.png?raw=true)
Go to log analytics and click on the log analytics that you created. 
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/993f332ef3d41772b2f255003563a3911f553b9f/Querying/Screenshot%202026-07-03%20030612.png)
Click on logs and exit out of Queries hub.
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/b64e961a825c87c868b7fbe0471119e060fa9b3a/Querying/Screenshot%202026-07-03%20030848.png)
click on sample mode and change it to KQL mode.
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/b15af6c8c3770a08b5c0d0eb417d106a62515316/Querying/Screenshot%202026-07-03%20031049.png)
Type security event and click the enter button
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/30f5ad0bdc029b4c5533f55d003fd356a9f66537/Querying/Screenshot%202026-07-03%20032222.png)
Type | Where Account == "for" and click the enter button
![Image alt](https://github.com/Kevinolee1/Querying-a-log-repository-with-KQL/blob/c254f256b7c39012d6f8ac84a8aa11bd1da42a51/Querying/Screenshot%202026-07-03%20032753.png)
Type | Project, Account, Computer, IpAddress and click on RUN
