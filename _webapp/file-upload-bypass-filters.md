---
layout: default
title: Bypassing Upload Filters
parent: File Upload Vulnerabilities
grand_parent: Web App Pentesting Notes and Methodology
---

# Bypassing Upload Filters

## Introduction

This page contains techniques for bypassing various types of file upload filters.

## Content-Type Validation Bypass

```bash
# Change content-type using Burp Suite
Content-Type: image/jpeg

Extension Validation Bypass
bash# Try these extensions
shell.php.jpg
shell.php%00.jpg
More techniques...

## Example Directory Structure
