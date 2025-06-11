# Slack-Salesforce Workflow Automation (In Development)

## Overview
This project integrates Salesforce with Slack to streamline sales team workflows. It enables sales reps to create and update Salesforce Opportunities directly from Slack using slash commands and receive real-time notifications for high-value leads and closed deals. The project leverages Salesforce’s REST API, Apex, Flow, and the Slack Bolt framework.

## Planned Features
- **Slack Slash Commands**: Use `/create-opp` to create Opportunities and `/update-opp` to update their stages in Salesforce.
- **Real-Time Notifications**: Send Slack messages for high-value leads (e.g., >$10,000) and closed Opportunities.
- **Automation**: Use Salesforce Flow to create follow-up tasks and trigger Slack notifications.
- **Analytics**: Build a Salesforce dashboard to track Slack-driven Opportunities and conversion rates.

## Tech Stack
- **Salesforce**: Apex, Flow, REST API, Salesforce Developer Edition
- **Slack**: Bolt framework, Node.js
- **Integration**: Salesforce REST API with OAuth 2.0

## Status
In development. Code for the Apex REST service and Slack app is implemented, with deployment and testing in progress.

## Code
- [Apex Class](classes/SlackSalesforceIntegration.cls): REST endpoints for Opportunity creation and updates.
- [Slack App](index.js): Node.js app with Slack Bolt for slash commands.
- [Metadata](classes/SlackSalesforceIntegration.cls-meta.xml): Salesforce metadata for the Apex class.

## Next Steps
- Deploy the Apex class to a Salesforce Developer Edition org.
- Configure and test the Slack app with a public Salesforce Site.
- Add a demo video and dashboard screenshots upon completion.

## Business Impact
- Reduces manual data entry by enabling Opportunity management from Slack.
- Targets a 20% improvement in lead response time through real-time notifications.

*Last updated: June 2025*
