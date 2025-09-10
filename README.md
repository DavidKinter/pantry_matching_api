# Recipe Pantry Matching API

A REST API that matches recipes to available ingredients in your pantry. Built with FastAPI and PostgreSQL.

## Problem

"What can we make for dinner with what we have?" - This API tells you which recipes you can cook based on your current ingredients.

## Solution

- Store your recipes with simple ingredient lists
- Update your pantry with available ingredients  
- Get instant matches showing what you can cook
- See missing ingredients and match percentages

## Tech Stack

- **FastAPI** - Modern Python web framework
- **PostgreSQL** - Database for recipes and users
- **JWT** - Secure authentication
- **SQLAlchemy** - Database ORM

## Core Features

1. **Recipe Storage** - Save recipes with ingredients as simple strings
2. **Pantry Management** - Track what ingredients you have
3. **Smart Matching** - Find recipes matching your pantry
4. **User Accounts** - Personal recipe collections with JWT auth

## Quick Start

```bash
# Clone repository
git clone <repository-url>
cd recipe-pantry-api

# Install dependencies
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# Configure environment
cp .env.example .env

# Run server
uvicorn main:app --reload
```

API documentation available at `http://localhost:8000/docs`

## Status

🟡 **Week 1 Complete** - Database schema and basic server setup done

---

Built as a 6-week bootcamp MVP project.