# jira-connectors

*This is not an official Google product*

This [Data Studio][data studio] conector let users consult [Jira Software][jira software] issues through their [REST API][rest api jira].

## Try the Community Connector in Data Studio

You can try out the managed deployment of the latest code: [Jira Conectors for Alchimia][production deployment]

### Connector configurations

| Text Field                     | Response                                                              |
|  ------------------------------|-----------------------------------------------------------------------|
| **User**                       | Email of the user with privileges in the projects to consult.         |
| **API Token**                  | The token generated by the user can be obtained in [Atlasin API Tokens][api tokens]|
| **Subdomain Jira Cloud**       | The domain that your cloud application uses. https://your-domain.atlassian.net|
| **Jira Query Language**        | Master filter to define projects, users etc... [Jira Query Language][jql]|

### Managed Fields

* key
* summary
* issuetype
* creator
* assignee
* reporter
* priority
* status
* created
* duedate
* resolutiondate
* components
* labels
* project
* satisfaction (customfield_10204)
* aggregatetimespent
* time to first response
* breached first response
* time to resolution
* breached time resolution

[jira software]: https://www.atlassian.com/software/jira
[rest api jira]: https://developer.atlassian.com/cloud/jira/platform/rest/v2/
[production deployment]: https://datastudio.google.com/datasources/create?connectorId=AKfycbwvwTvbxhKVCZG05st2GH5rxYU8Syds36Y_9spZp3tq
[api tokens]: https://id.atlassian.com/manage/api-tokens
[data studio]: https://datastudio.google.com
[jql]: https://confluence.atlassian.com/jiracoreserver/advanced-searching-939937709.html?_ga=2.120070472.1524126525.1544574940-1266246199.1525106444