---
id: what-is-an-activity-id
title: What is an Activity Id?
sidebar_label: Activity Id
description: A unique identifier for an Activity Execution.
tags:
  - term
  - explanation
---

The identifier for an [Activity Execution](/concepts/what-is-an-activity-execution).
The identifier can be generated by the system, or it can be provided by the Workflow code that spawns the Activity Execution.
The identifier is unique among the open Activity Executions of a [Workflow Run](/concepts/what-is-a-run-id/).
(A single Workflow Run may reuse an Activity Id if an earlier Activity Execution with the same Id has closed.)

An Activity Id can be used to [complete the Activity asynchronously](/concepts/what-is-asynchronous-activity-completion/).
