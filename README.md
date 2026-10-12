# Linux File and Directory Permission Audit and Hardening

## Overview

This project examines Linux file and directory permissions through POSIX permission analysis and targeted `chmod` operations.

It focuses on the **Principle of Least Privilege**, which limits access to the permissions necessary for intended tasks. Proper permission management helps reduce unauthorized modification, unnecessary access, and risks associated with excessive privileges.

## Objectives

- Analyze owner, group, and others permissions.
- Review file write access and directory traversal permissions.
- Apply and evaluate symbolic `chmod` operations.
- Verify permission states and document findings accurately.

## Tools and Concepts

- **Environment:** Kali Linux
- **Tools:** `ls`, `chmod`
- **Concepts:** POSIX permissions, access control, Least Privilege, permission verification

## Key Findings

The assessment examines permissions on `project_k.txt`, `.project_x.txt`, and the `drafts` directory. It also highlights why initial and final permission states must be compared before claiming that a security issue has been remediated.

## Report

See [`report/permission-audit-report.pdf`](report/permission-audit-report.pdf) for the full technical report.

## Scope

This project was conducted in a controlled learning environment and focuses on selected Linux file system permissions. Findings are limited to the permission states and evidence documented in the report.
