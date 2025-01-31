<h1 align="center">ChatGPT Web Share</h1>

<div align="center">

[![Github Workflow Status](https://img.shields.io/github/actions/workflow/status/moeakwak/chatgpt-web-share/docker-image.yml?label=build)](https://github.com/moeakwak/chatgpt-web-share/actions)
[![License](https://img.shields.io/github/license/moeakwak/chatgpt-web-share)](https://github.com/moeakwak/chatgpt-web-share/blob/main/LICENSE)

A web application that allows multiple users to share a ChatGPT account at the same time, developed using FastAPI and Vue3.

Used for sharing one ChatGPT account among friends.

</div>


This readme was mainly translated by ChatGPT.

## About the project

Mai WebChat is designed to share a ChatGPT Plus account with multiple users. CWS:
- is a front-end and back-end separated application
- is used to share a ChatGPT account, not the official API
- supports user and conversation managements
- prioritizes support for ChatGPT Plus accounts

## Features

- A beautiful and concise web interface using [naive-ui](https://www.naiveui.com/)
  - Supports English language
  - Supports switching to dark mode
  - Supports copying reply content or code content with one click
  - Supports displaying images, tables, mathematical formulas, and code highlighting in replies
  - Supports exporting conversations as beautiful Markdown or PDF files
  - Replying content in typing animation
  - Supports stopping generation
- Multiple users can share the same ChatGPT account
  - Different users' ChatGPT conversations are separated and do not affect each other
  - When multiple users request at the same time, they will be queued for processing
  - Administrators can set users' maximum number of conversations, conversation time limits, etc.
  - Provides real-time updated service usage status to avoid usage peaks
- Comprehensive management functions
  - Modify user conversation restrictions
  - Manage conversations/view member conversation records/assign conversations to specific users
  - View logs in real-time
  - Record request and conversation statistics

## Deploy Guide

## Usage Statement

### Information Collection and Privacy Statement

### Risk Statement

This project is for learning and research purposes only, and commercial use is not encouraged. We are not responsible for any losses caused by using this project.
