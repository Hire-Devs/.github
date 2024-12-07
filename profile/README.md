# Discord Dev Bot

## Overview

The **Discord Dev Bot** is a versatile tool designed for Discord communities to facilitate easy job searching and hiring. The bot allows users to create profiles, post job listings, search for relevant job opportunities, and set reminders for upcoming job-related tasks. It provides a user-friendly way to interact with the job market directly within Discord servers.

## Why This Bot?

In many Discord communities, developers and professionals often struggle to find the right opportunities or the right people for their projects. This bot aims to bridge that gap by making it easier for users to share their skills, post job listings, and even set reminders for job-related tasks, all without leaving Discord. 

The bot also provides a way to **connect job seekers** with employers in a direct, convenient, and seamless manner.

## Features

### 1. **User Profiles**
   - Users can create and manage a **personal profile** with their skills, which employers can view when searching for candidates.
   - Use the `/create_profile` command to set up or update your profile.
   - View your profile anytime with the `/show_profile` command.

### 2. **Job Listings**
   - Employers can **post job openings** with details such as required skills, salary, and job description.
   - Use the `/post_job` command to create a job listing that will be visible to the community.
   - Users can **search job listings** using keywords related to required skills.
   - Use the `/search_jobs` command to find available opportunities.

### 3. **Job Reminders**
   - Users and employers can **set reminders** for job-related tasks like application deadlines or job expirations.
   - Reminders will notify users about important updates related to jobs.
   - Use the `/job_reminder` command to set or receive reminders.

### 4. **Slash Commands**
   - The bot supports **slash commands** (e.g., `/create_profile`, `/post_job`), making it easy for users to interact with the bot.

### 5. **Embedded Responses**
   - The bot responds with **rich embedded messages** containing detailed job listings, profiles, and more, making the user experience much more visual and engaging.

## How to Use the Bot

1. **Invite the Bot to Your Server**:
   - To get started, invite the bot to your Discord server by using the invite link provided by the bot owner (you can use the "OAuth2" page in the Discord Developer Portal to create the invite link).

2. **Create Your Profile**:
   - Use the `/create_profile` command to create a profile and share your skills with potential employers.

3. **Post a Job**:
   - If you're an employer, use `/post_job` to share job openings in the server.

4. **Search for Jobs**:
   - To find job opportunities, use `/search_jobs <keyword>` to search for jobs based on required skills.

5. **Set Job Reminders**:
   - Use `/job_reminder` to receive reminders about job postings, application deadlines, or expirations.

## Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - `discord.py` for interacting with the Discord API
  - `pymongo` for storing user profiles and job listings in a MongoDB database
  - `dotenv` for managing environment variables
- **Database**: MongoDB (cloud-based) for storing profiles and job listings

## Who Created This Bot?

This bot was created by **Anshuman Mishra** aka **Pg Network**. 

Anshuman is a developer with expertise in **HTML, CSS, JavaScript, Python, PHP**, and **SQL**. The goal of creating this bot was to provide a useful tool for Discord communities, helping users easily find and post job opportunities.

## Contributing

Contributions are welcome! If you want to improve this bot, feel free to fork this repository and submit a pull request with your changes.

### Guidelines:
- Ensure your code is well-commented.
- Add unit tests where applicable.
- Make sure your changes don't break the bot's functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feel free to reach out via:

- Email: [anshumanmishra799@gmail.com](mailto:anshumanmishra799@gmail.com)
- Discord: [Pg Network](https://discord.gg/XAZgdrR6k6)
