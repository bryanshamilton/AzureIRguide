---
name: Azure Fraud Advisory Investigation Guide
tagline: A step-by-step playbook for Arrow partners to investigate and resolve Azure fraud alerts
category: Enablement
status: maintained
# TODO (repo owner): confirm the executive sponsor accountable for this solution
# exec_sponsor:
# TODO (repo owner): confirm stakeholder teams/functions
# stakeholders:
#   -
audience: Arrow Electronics CSP partners financially responsible for customer Azure consumption
problem: >
  As a CSP partner you are financially liable for your customers' Azure consumption. When
  Microsoft issues an Azure fraud advisory — crypto mining, anomalous compute, or account
  takeover — failing to investigate quickly can mean large unauthorized charges, compromised
  customer environments, compliance violations, and lost trust.
solution: >
  An end-to-end investigation guide that takes partners from validating an alert through
  Activity Log, cost-anomaly, and Entra sign-in review to classification, remediation, and
  prevention — with advanced SOC and Microsoft Sentinel KQL guidance for deeper analysis.
highlights:
  - Eight-step investigation workflow from alert to resolution
  - Covers all four alert channels (email, dashboard, webhook, Graph API)
  - Remediation playbook for confirmed fraud
  - Advanced SOC analyst section with Sentinel setup and KQL queries
  - Preventive measures and partner FAQ
tech:
  - Microsoft Azure
  - Microsoft Partner Center
  - Microsoft Sentinel
  - Microsoft Graph Security Alerts API
links:
  repo: https://github.com/naccoe-docsNtools/AzureIRguide
---

# Azure Fraud Advisory Investigation Guide

A step-by-step playbook for Arrow partners to investigate and resolve Azure fraud alerts.
