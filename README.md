# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b9d1c55759bda25efa5eb7_user:%24JHKANf%23m0eBr%26Yyx7f4%21%23%259%23m2BbfZq@ep-rapid-scene-akl6jtdu.c-3.us-west-2.aws.neon.tech:5432/AppDB_69b9d1c55759bda25efa5eb7?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b9d1c55759bda25efa5eb7-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b9d1c55759bda25efa5eb7-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
