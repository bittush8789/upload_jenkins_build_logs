Jenkins Build Logs Automation to Amazon S3
Project Overview

This project automates the collection of Jenkins job build logs from a Linux-based Jenkins server and uploads them daily to Amazon S3 using Bash scripting and AWS CLI.
It helps in centralized log storage, faster troubleshooting, and improved CI/CD monitoring.

Key Features

Automatically scans all Jenkins jobs and build directories
Uploads only the current day’s Jenkins build logs
Uses standardized naming conventions for easy log identification
Validates AWS CLI installation before execution
Eliminates manual log handling in CI/CD pipelines

Technologies Used

Linux
Bash / Shell Scripting
Jenkins
AWS S3
AWS CLI
