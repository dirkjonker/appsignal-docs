---
title: "Integrations"
---

Besides email notifications we can send messages about new exceptions, performance issues and deploys to several 3rd parties. Below is a list of supported external services.

To enable notifications and issue tracker integration for external services, go to the ["Notifications" page](https://appsignal.com/redirect-to/app?to=notifiers) or the ["Integrations" page](https://appsignal.com/redirect-to/app?to=integrations) in the app navigation and fill out the form for each service you'd like to enable.

## Available integrations

- [Asana](/application/integrations/asana.html)
- [Clubhouse](/application/integrations/clubhouse.html)
- [Discord](#discord)
- [Flowdock](#flowdock)
- [Geckoboard](#geckoboard)
- [GitHub](#github)
- [GitLab](#gitlab)
- [Google Hangouts Chat](#google-hangouts-chat)
- [HipChat](#hipchat)
- [Intercom](#intercom)
- [Jira](#jira)
- [OpsGenie](#opsgenie)
- [PagerDuty](/application/integrations/pagerduty.html)
- [Phabricator](#phabricator)
- [Pivotal Tracker](#pivotal-tracker)
- [Slack](/application/integrations/slack.html)
- [Trello](#trello)
- [Webhook](/application/integrations/webhooks.html)

## Discord

All-in-one voice and text chat for gamers that's free, secure, and works on both your desktop and phone.

We support Discord through their [Slack-compatible webhook](https://discordapp.com/developers/docs/resources/webhook#execute-slackcompatible-webhook). To enable it, [find your webhook URL](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks), append `/slack` to it, and use it as the webhook URL in our [Slack](#slack) integration.

Website: [https://discordapp.com](https://discordapp.com)

## Flowdock

Chat & inbox for teams. One place to talk and stay up-to-date.

Website: [https://www.flowdock.com](https://www.flowdock.com)

## Geckoboard

Use Geckoboard to build clear, effective data dashboards for your business that keep teams informed, motivated and aligned around your KPIs.

Website: [https://www.geckoboard.com/](https://www.geckoboard.com/)

## GitHub

GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers. Over six million people use GitHub to build amazing things together.

Website: [https://github.com](https://github.com)

## GitLab

Tools for modern developers.

GitLab unifies issues, code review, CI and CD into a single UI.

This integration does not automatically create issues on GitLab, to prevent story-overload.

The following API scopes will be needed for the GitLab integration:

- `read_user`
- `api`

Website: [https://gitlab.com](https://gitlab.com)

## HipChat

Group chat and video chat built for teams.

Website: [https://www.hipchat.com](https://www.hipchat.com)

## Intercom

[Intercom](https://intercom.io) is one place for your entire business to see and talk to customers. Have live conversations and send targeted messages to website visitors and users of your app.

Website: [Intercom](https://intercom.io)

For detailed information about setting up Intercom, visit the [Intercom page](/application/integrations/intercom.html).

## Jira

[Jira](https://www.atlassian.com/software/jira) by Atlassian is a tracker for teams that plan and build products. It’s available as a self-hosted and cloud hosted solution.

Website: [Jira](https://www.atlassian.com/software/jira)

For detailed information about setting up (self)hosted Jira, visit the [Jira page](/application/integrations/jira.html).

## OpsGenie

OpsGenie is an alerting and on-call management solution that provides Dev & Ops teams with flexible schedule management, escalations and alerting via email, SMS, and mobile app notifications.

Website: [https://www.opsgenie.com/](https://www.opsgenie.com/)

## Phabricator

Phabricator is a suite of web-based software development collaboration tools, including the Differential code review tool, the Diffusion repository browser, the Herald change monitoring tool, the Maniphest bug tracker and the Phriction wiki.

Website: [https://phacility.com/phabricator/](https://phacility.com/phabricator/)

## Pivotal Tracker

Simple, collaborative project management from the experts in agile software development.

Website: [http://www.pivotaltracker.com/](http://www.pivotaltracker.com/)

## Trello

Trello makes it easy to organize anything with anyone.

Website: [https://trello.com](https://trello.com)
