


-----

# DevOps Ticket Resolution Playbooks

This repository serves as a centralized, living knowledge base for DevOps and Site Reliability Engineering (SRE) teams. It contains a collection of detailed playbooks for diagnosing and resolving common P3 (Priority 3) tickets, which typically involve issues that are important but not immediately service-impacting.

The primary goal of this repository is to streamline the troubleshooting process, standardize resolution methods, and empower team members with clear, actionable guidance. By documenting solutions and workflows, we aim to reduce resolution time, minimize cognitive load, and promote consistency across the team.

## Table of Contents

  - [How to Use This Repository](https://www.google.com/search?q=%23how-to-use-this-repository)
  - [Repository Structure](https://www.google.com/search?q=%23repository-structure)
  - [Ticket Playbooks](https://www.google.com/search?q=%23ticket-playbooks)
  - [Contributing](https://www.google.com/search?q=%23contributing)

## How to Use This Repository

To effectively use this playbook, follow these steps:

1.  **Identify the Ticket:** When a P3 ticket is created, find the corresponding Markdown file in the `tickets` directory. The files are named for easy searching.
2.  **Review the Problem:** Read the **Problem Description** and **Possible Root Causes** to quickly understand the issue and its potential origins.
3.  **Follow the Workflow:** Use the **Troubleshooting Workflow** diagram to visually navigate the systematic steps for diagnosis. This helps in logically ruling out common causes.
4.  **Execute the Solutions:** Refer to the **Detailed Solution Steps** section for specific commands, checks, and actions to take on the relevant systems. The solutions are ordered from the most likely to the least likely cause.
5.  **Contribute:** If you discover a new or more efficient solution, please contribute by submitting a Pull Request.

## Repository Structure

The repository is organized into a single `tickets` directory, with one Markdown file for each ticket. Each file is a self-contained playbook for a specific issue.

```
devops-ticket-playbooks/
├── tickets/
│   ├── 1-missing-linux-syslog-events.md
│   ├── 2-no-amp-data-available.md
│   ├── 3-ccd13-clusters-log-events.md
│   ├── 4-connection-to-apm-down.md
│   ├── 5-my-new-rules-are-no-more-running.md
│   ├── 6-incorrect-parsing-lodo-otn.md
│   ├── 7-new-kafka-topic-to-be-processed.md
│   ├── 8-parsing-error-soc-windows.md
│   ├── 9-current-buffer-size-settings.md
│   ├── 10-use-more-s3-buckets.md
│   ├── 11-solcon-logging-not-seen.md
│   ├── 12-logging-for-lodo-lbs-not-seen.md
│   └── 13-elastic-kibana-radius-account-issue.md
└── README.md
```

## Ticket Playbooks

A list of all P3 tickets documented in this repository:

| ID | Ticket Name | Status |
| :-- | :--- | :--- |
| **001** | [Missing Linux Syslog events](https://www.google.com/search?q=tickets/1-missing-linux-syslog-events.md) | **Complete** |
| **002** | [No AMP data available anymore](https://www.google.com/search?q=tickets/2-no-amp-data-available.md) | **Complete** |
| **003** | [CCD13 clusters log events not visible in Kibana](https://www.google.com/search?q=tickets/3-ccd13-clusters-log-events.md) | **Complete** |
| **004** | [Connection to APM down](https://www.google.com/search?q=tickets/4-connection-to-apm-down.md) | **Complete** |
| **005** | [My new rules are no more running](https://www.google.com/search?q=tickets/5-my-new-rules-are-no-more-running.md) | **Complete** |
| **006** | [Incorrect parsing noticed for lodo OTN](https://www.google.com/search?q=tickets/6-incorrect-parsing-lodo-otn.md) | **Complete** |
| **007** | [New kafka topic to be processed](https://www.google.com/search?q=tickets/7-new-kafka-topic-to-be-processed.md) | **Complete** |
| **008** | [Parsing error in the index soc-windows](https://www.google.com/search?q=tickets/8-parsing-error-soc-windows.md) | **Complete** |
| **009** | [Current buffer size settings s3 repositories](https://www.google.com/search?q=tickets/9-current-buffer-size-settings.md) | **Complete** |
| **010** | [We would like you to use more s3 buckets for distributing load](https://www.google.com/search?q=tickets/10-use-more-s3-buckets.md) | **Complete** |
| **011** | [Solcon logging is not being seen in Elastic](https://www.google.com/search?q=tickets/11-solcon-logging-not-seen.md) | **Complete** |
| **012** | [Logging for lodo lbs is not being seen in Elastic](https://www.google.com/search?q=tickets/12-logging-for-lodo-lbs-not-seen.md) | **Complete** |
| **013** | [Elastic/Kibana Arrange RADIUS account issue](https://www.google.com/search?q=tickets/13-elastic-kibana-radius-account-issue.md) | **Complete** |

