# USER: Unified Standard for Electronic Resumes

## Introduction
USER is a standardized, human-readable data format designed specifically for electronic resumes. By providing a common structure for resume data, USER simplifies the process of creating, sharing, and parsing resumes, making it easier for job seekers and recruiters to interact.

## Why USER?
* **Standardized:** Provides a consistent format for resumes, making it easier for systems to process and compare.
* **Human-readable:** YAML syntax makes it easy for humans to read and write.
* **Flexible:** Can be extended to accommodate various resume formats and industry-specific requirements.
* **Open:** The format is open-source and community-driven, allowing for continuous improvement.

## Basic Structure
A USER resume consists of a YAML file with the following basic structure:

```yaml
name: Your Name
email: [endereço de e-mail removido]
phone: +1 (123) 456-7890
summary: A brief summary of your skills and experience.
skills:
  - Python
  - JavaScript
  - React
experience:
  - company: Company Name
    position: Software Engineer
    start_date: 2020-01-01
    end_date: 2023-12-31
    description: ...
education:
  - institution: University Name
    degree: Bachelor of Science
    field: Computer Science
    year: 2023
