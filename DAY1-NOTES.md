# Day 1 - Voting App

## Objective
Run the starter Voting App locally using Docker Compose.

## Environment
* Operating system: Windows
* Container runtime: Docker
* Source control: Git and GitHub

## What I verified
* The repository was cloned from my GitHub fork.
* The Git remote points to my fork.
* Docker Compose configuration is valid.
* The voting page loads locally.
* The results page loads locally.
* The containers are running.

## Architecture
* Vote service: accepts votes from users.
* Redis: queues votes for processing.
* Worker: transfers processed votes to the database.
* PostgreSQL: stores vote data.
* Result service: displays the totals.

