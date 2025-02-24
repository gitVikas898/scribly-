# scribly

# Collaborative Document Editor

A real-time collaborative document editor that allows multiple users to edit documents simultaneously—similar to Google Docs.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
  - [Backend (Java)](#backend-java)
  - [Frontend (React)](#frontend-react)
- [API Endpoints](#api-endpoints)
- [Real-Time Collaboration](#real-time-collaboration)
- [Collaboration & Workflow](#collaboration--workflow)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **Real-Time Editing:** Multiple users can work on the same document concurrently.
- **Rich Text Editing:** Supports formatting, lists, links, and other rich text features.
- **User Authentication:** Secure login and registration using JWT and Spring Security.
- **Document Management:** Create, update, and retrieve document content.
- **Conflict Resolution:** Merge changes using operational transformation (OT) or CRDT algorithms.

## Tech Stack

### Frontend
- **React:** For building a dynamic user interface.
- **Rich Text Editor Libraries:** [Slate.js](https://docs.slatejs.org/), [Draft.js](https://draftjs.org/), or [ProseMirror](https://prosemirror.net/).
- **Real-Time Collaboration:** Integration with libraries such as [Yjs](https://yjs.dev/) or [ShareDB](https://share.github.io/sharedb/) and WebSocket clients.

### Backend (Java)
- **Spring Boot:** For creating RESTful APIs and WebSocket endpoints.
- **Spring WebSocket & STOMP:** For real-time, bi-directional communication.
- **Spring Security with JWT:** For secure authentication.
- **Database:** MongoDB (using Spring Data MongoDB) or a relational database (using Spring Data JPA).

## Prerequisites
- **Java 11+**
- **Maven** or **Gradle**
- **Node.js & npm**
- **MongoDB** (or another preferred database)

## Installation & Setup

### Backend (Java)
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/collaborative-doc-editor.git
   cd collaborative-doc-editor/backend
### Frontend(React)
