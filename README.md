## QA Test Notes:
BE Release: release-2025-07-29   Version: 450.29

FE Release: fe-release-2025-07-29

Note: The Datasource permission tests have been conducted with the BE release: release-2025-07-29 and the Product Features (including Glean AI), functional and UI tests have been conducted with the FE release:fe-release-2025-07-29. These test logs are consolidated results from both the releases.

### Datasource
|Datasource|Test Description|Testing Status|
|:-------:|-------|:-------:|
|Aha|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Airtable|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Asana|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Bitbucket|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Box|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Confluence Cloud|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Confluence Server|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|GDrive|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Databricks|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|DocuSign|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Docebo|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Dropbox|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Egnyte|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Freshservice|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Gcal|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Github|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Gitlab|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|GMail|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Gong|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Google Groups|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Google Sites|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Greenhouse|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Guru|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Hubspot|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Jira Cloud|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Jira Server|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Linear|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Looker|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Lucid|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Lumapps|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Miro|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Monday|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Msteams|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Notion|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|OneDrive|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Outlook|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Outlook Calender|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Salesforce|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|ServiceNow|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|SharePoint|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Simpplr|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Slack|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Slack Enterprise|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Smartsheet|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Tableau|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Trello|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Wordpress|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Yammer|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Zendesk|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|
|Zoom|All Permissions and Content fetch from Datasource maintained|:white_check_mark:|


### Security
|Security|Test Description|Testing Status|
|:-------:|-------|:-------:|
|Endpoint Testing|Client and Admin endpoint auth validations. Validations for green listed IP addresses and rate limiting|:white_check_mark:|
|Rest API Testing|Public rest API endpoints auth validations|:white_check_mark:|
|IPJC Testing|Validations on secure communication between deployment projects and central project|:white_check_mark:|
|Slack Glean Bot Testing|Auth validation for endpoints exposed for Slack Glean bot|:white_check_mark:|
|Action Pack Testing|Auth validation for endpoints required for authorisation of Actions|:white_check_mark:|
|Internal debug portal Testing|Auth validation for internal debug endpoints|:white_check_mark:|


### Features (including AI)
|Features|Test Description|Testing Status|
|:-------:|-------|:-------:|
|Workspace Setup|App Connections|:white_check_mark:|
|Embedded Flows|Functional + UI checks on Embedded Search/ AI entry points with different configurations on internal sandbox instance|:white_check_mark:|
|Admin Features|Functional + UI checks on Insights, Datasource setup, Admin Search, Admin Alerts, Platform Setup|:white_check_mark:|
|Data Governance| Functional + UI checks on AI Governance, Content Hiding, Access Verification, Sensitive Findings and reports|:white_check_mark:|
|Entities|Functional + UI checks on People data, Teams data, Org Chart|:white_check_mark:|
|Search|Search features, including search aid and autocomplete|:white_check_mark:|
|Home Page / New Tab Page|Functional+UI checks on Login/Logout, NUX, Home Page sections|:white_check_mark:|
|Onboarding flow|Functional+UI Checks on the Onboarding checklist flow |:white_check_mark:|
|Extension features|Functional+ UI checks on Native Search Replacement, Sidebar, New Tab Page|:white_check_mark:|
|User Generated Content|Functional (CRUD) + UI checks on Answers, Collections, Announcements, Golinks, Pinning|:white_check_mark:|
|Glean Chat|Functional + UI checks on Glean Chat features including World Mode, Company Mode, All Mode, Deep Research, and other Glean Chat features|:white_check_mark:|
|AI Summaries|Functional + UI checks on all AI Summaries entry points|:white_check_mark:|
|AI Answers|Functional + UI checks on all AI Answers entry points|:white_check_mark:|
|Glean Slackbot|Functional + UI checks on Proactive and Reactive Glean Search / Glean AI Slackbot|:white_check_mark:|
|Glean Assist|Functional + UI checks on Assist widgets on ServiceNow, Zendesk and Salesforce / Glean AI Slackbot|:white_check_mark:|
|Self Serve Glean AI setup|Functional + UI check on Self Serve Glean AI features|:white_check_mark:|
|Glean Actions|Functional + UI check on OOTB Action Packs, Action creation from scratch|:white_check_mark:|
|Glean Agents|Functional + UI checks on Glean Agents|:white_check_mark:|
