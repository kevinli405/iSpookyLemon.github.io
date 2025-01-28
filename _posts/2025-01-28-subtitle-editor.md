---
layout: post
title: "Subtitle Editor"
date: 2025-01-28
description: "Web app for creating and editing subtitles for videos - Winter 2025"
permalink: "subtitle-editor"
tags: [React, CSS, Javascript, Flask, FFmpeg, Axios, Vercel, Render]
---

![Website Screenshot](assets/images/subtitleeditor.png)

This web app was inspired by my personal experiences as a music producer on TikTok, where I relied on CapCut for video editing. However, with CapCut facing potential shutdown due to the TikTok ban, I created a custom web solution for video editing and subtitle management.

The app empowers users to upload videos, edit or generate subtitles, and download processed videos with their subtitles seamlessly integrated. Built with React, Flask, and Tailwind CSS, the app utilizes advanced tools like Vercel for deployment and axios for robust API communication. This project reflects my commitment to creating intuitive, functional tools tailored to creative workflows, drawing from my own needs as a content creator.

Key features include:

Real-Time Subtitle Editing: Edit subtitle text, start and end times, and preview changes alongside the video.

Responsive Design: Optimized for various screen sizes using modern CSS techniques.

Backend Video Processing: Leveraged FFmpeg and Flask to embed subtitles into the video seamlessly.

File Upload and Download: Handles video file uploads and returns processed videos as downloadable links.

Deployment: The frontend is hosted on Vercel, while the backend is deployed on Render, ensuring a smooth and scalable user experience.


- **Technologies**: React, CSS, Javascript, Flask, FFmpeg, Axios, Vercel, Render
- **Publication Link**: [https://autocaption-seven.vercel.app/](https://autocaption-seven.vercel.app/)