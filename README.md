TAPAS – Tap-And-Presence Attendance System  
=========================================  

> ⚠️ Work in progress: Expect breaking changes and incomplete features.  

## Overview  

TAPAS (**T**ap‑**A**nd‑**P**resence **A**ttendance **S**ystem) is an experimental toolkit to support lecturers using Google Classroom in **physical** teaching environments. Its main goal is to make it easy to:  

- Track **in‑room attendance** via tap/NFC–style check‑ins.  
- Automatically assign **quizzes only to students who are physically present**, reducing cheating by remote participants who are not actually in the classroom.  

This repository is in active development and not ready for production use. Interfaces, data structures, and deployment steps may change frequently.  

## Core idea  

Traditional online quizzes in Google Classroom can be completed from anywhere, which makes it hard to distinguish between:  

- Students who are **physically present** in the classroom.  
- Students who are completing quizzes **remotely** without attending the session.  

TAPAS aims to link **attendance events** (e.g., NFC or tap‑in at the classroom door) with **quiz assignment** so that:  

- Only students who **checked in physically** are automatically assigned the associated quiz.  
- Remote students cannot simply join late or from home and gain the same credit as those who attended in person.  

## Current status  

This project is currently:  

- **Pre‑alpha / proof‑of‑concept**.  
- Missing full configuration, documentation, and error handling.  
- Likely to change in folder structure, function names, and required permissions.  

Use it as a starting point, code sketch, or inspiration rather than a finalized solution.  

## Planned features  

Planned (but not yet guaranteed or stable) features include:  

- ??

## Intended audience  

TAPAS is designed primarily for:  

- Lecturers using Google Classroom in **face‑to‑face** or **hybrid** courses.  
- Educators who want to **discourage cheating** by making quiz participation depend on **physical attendance**.  
- Technically comfortable users who are willing to experiment with early‑stage scripts and workflows.  

## Disclaimer  

- This repository is a personal/experimental project, not an official Google product.  
- Use at your own risk; you are responsible for complying with your institution’s policies and privacy regulations.  

More detailed setup and usage instructions will be added as TAPAS evolves.