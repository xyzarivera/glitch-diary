# Design Doc

This is the design document for Glitch Diary.
Version: MVP

## Context

Glitch Diary is a blog project. It's easy to just pull an existing
project and blog right away. But the main goal is for @xyzarivera to
practice iterative development and software engineering fundamentals through
this project.

The project should start from the most simple way to blog. A simple user 
interface and a server with data persistence.

## Goals 

### As a user
- I should be able to bring the Raspberry Pi and use the app anywhere
- I should be able to submit a log entry
- I should be able to see the list of logs

### As an engineer

- I should be able to develop an application without using 
frontend libraries (ReactJS, Vue, Sveltte) or meta-frameworks (NextJS, NuxtJS,
Sveltte Kit)
- I should be able to use modern CSS by not using pre-processors or utility 
classes
- I should be able to deploy an application in a bare-metal
environment
- I should be able to set up and use a relational database.
- I should be able to write a design document for the MVP
- I should be able to write tickets with proper scope and acceptance criteria

## Features

The user interface should be able to 
  - display all logs
  - accept new logs using a form
  - submit new logs to the server

The server should be able to
  - create new logs sent from the interface
  - persist the new log in a storage
  - read all saved logs

## Scope limitations
These features are not yet covered:
  - interface design
  - reading individual logs
  - updating logs
  - deleting logs
  - testing 

## Architecture

The user interface will be developed using HTML, CSS, and JS/TS.

The server will be developed using the ExpressJS framework with a PostgreSQL
database and REST API.

## Deployment

Both user interface and server will be deployed in a Raspberry Pi.

