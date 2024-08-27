# Teacher Sandbox Creation and Enrollment Tool

## Overview
This tool automates the creation of sandbox courses for instructors in Canvas who are enrolled as teachers in any course or section. It also enrolls these instructors into a self-paced course specifically designed for them. The script checks if a sandbox already exists for an instructor before creating a new one, ensuring that no duplicate sandboxes are created.

## Purpose
- **Sandbox Creation**: Automatically creates sandbox courses for instructors who do not already have one.
- **Self-Paced Course Enrollment**: Enrolls instructors into a self-paced course, ensuring they have access to essential training and resources.
- **Efficiency**: The tool processes large numbers of courses and instructors efficiently, using progress tracking and logging to keep track of operations.

## Features
- **Canvas API Integration**: Connects to the Canvas LMS to retrieve course and instructor data.
- **Automated Sandbox Creation**: Creates sandboxes in a specified subaccount for instructors who do not have one.
- **Automated Enrollment**: Enrolls instructors into a self-paced course if they are not already enrolled.
- **Logging**: Records the actions taken (sandbox creation, enrollment) in a CSV file.

## Requirements
- Python 3.x
- Required Python packages:
  - `canvasapi`
  - `configparser`
  - `tqdm`
  - `csv`
- Access to a Canvas LMS instance
- Configuration of a `config.ini` file with necessary credentials and URLs.
