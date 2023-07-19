# Assign fix work

## Introduction

{% hint style="info" %}
**Recap**\
You have understood and fixed a vulnerability.
{% endhint %}

This section describes how this fix process works throughout your team for your applications.

* [Decide what to fix first](assign-fix-work.md#decide-what-to-fix-first): determine your team fix priorities.
* [Decide your fix workflow](assign-fix-work.md#example-workflow-team-lead-driven-using-jira): for example, using a Jira-driven process.

### Decide what to fix first

Your fix priority depends on your workflows and business processes. Different teams approach fixes in different ways, depending on the tools they use, their own workflow maturity, and competing work priorities.

Typically, smaller teams have less process, and Enterprise-level teams are more formal. For example, individual developers in your teams may decide which issues to fix on a case-by-case basis, or it may be a more controlled process, with team leads assigning fix work as part of a Sprint planning process

#### Example triage process

For example, your team could follow a triage-based process for each issue, driven largely by the severity of the issue:

<figure><img src="../../.gitbook/assets/image (23) (2).png" alt="Using a triage process for issues"><figcaption><p>Using a triage process for issues</p></figcaption></figure>

### Example workflow: team-lead driven, using Jira

{% hint style="info" %}
**Feature availability**\
Jira integration is available with all paid plans. See [pricing plans](https://snyk.io/plans/) for more details.
{% endhint %}

Some teams base all their work around Jira tasks; we’ll look at this as an example.

Let’s assume that your development team assigns fix work based on Sprints, and decides that the next development Sprint will be dedicated to vulnerability fixing.

As part of this Sprint planning, the team leader can:

* Review the vulnerabilities in a project
* Decide which vulnerabilities to fix
* Create a Jira issue for each vulnerability.
* Assign these Jira issues as task to developers to fix these vulnerabilities,
* Track progress on these tasks during the Sprint.

Snyk [Jira integration](../../integrations/notifications-ticketing-system-integrations/jira.md) allows you to run this process from the Snyk Web UI.

#### Assign a Jira issue

Navigate to the issue you have decided to fix, then click **Create a Jira issue**:

<figure><img src="../../.gitbook/assets/image (221) (1).png" alt="Create a Jira issue"><figcaption><p>Create a Jira issue</p></figcaption></figure>

You can then define the Jira task details for this fix:

<figure><img src="../../.gitbook/assets/image (302).png" alt="Create a Jira issue details"><figcaption><p>Create a Jira issue details</p></figcaption></figure>

You can assign this task to a developer in the team, following your team’s normal Sprint processes.

{% hint style="info" %}
You may want to create a Jira issue even if Snyk knows how to fix the change, and even if it’s a very minor upgrade; assigning issues allows your team to manage, justify and track code changes.
{% endhint %}

#### More information

* See [Jira issues](https://training.snyk.io/learn/video/jira-issue) training for more details.
* See [Manage issues](../../manage-issues/) docs for more general details.

### What's next?

Now, you can look at [using Snyk Reports to manage team work](manage-team-work-using-reports.md).
