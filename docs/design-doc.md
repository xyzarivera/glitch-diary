# Design Doc

This is the design document for Glitch Diary.
Version: MVP

## Context

Glitch Diary is a blog project. It's easy to just pull an existing
project and blog right away. But the main goal is for @xyzarivera to
practice iterative development and software engineering fundamentals through
this project.

The project should start from the most simple way to blog. A simple interface
and a server with data persistence.

## Goals
Be able to develop the following features:

The interface should be able to 
  - display all logs
  - accept new logs using a form
  - submit new logs to the server

The server should be able to
  - create new logs sent from the interface
  - persist the new log in a storage
  - read all saved logs

## Non-Goals
These features are not yet covered:
  - interface design
  - reading individual logs
  - updating logs
  - deleting logs

## Architecture

The interface will be developed using HTML, CSS, and JS/TS.

The server will be developed using the ExpressJS framework with a PostgreSQL
database and REST API.

