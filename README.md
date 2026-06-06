# Enterprise-AI-Prediction-Workflow
AI-powered enterprise prediction workflow using Snowflake, OpenAI/LangChain, Python, and FastAPI to convert natural-language business questions into structured forecasting API calls

## Overview
This project demonstrates an enterprise AI workflow that connects Snowflake data, Python ML prediction services, and an OpenAI/LangChain natural-language interface. The goal was to help non-technical business users ask forecasting questions in plain English and receive structured price or demand predictions.

## Problem
Business users often need SQL knowledge or API formatting skills to access enterprise prediction models. This creates friction between data systems, ML models, and business decision-making.

## Solution
I built a Snowflake-backed AI workflow that:
- Connects to structured enterprise data in Snowflake
- Trains price and demand forecasting models
- Deploys prediction models as reusable FastAPI services
- Uses OpenAI/LangChain to classify user intent and extract required fields
- Routes natural-language questions to the correct prediction endpoint
- Validates inputs before returning AI-powered outputs

## Tech Stack
- Snowflake
- SQL
- Python
- OpenAI API
- LangChain
- FastAPI
- Uvicorn
- Postman
- Machine Learning Models

## Key Features
- 2 reusable forecasting APIs: price prediction and demand prediction
- Natural-language `/ask` interface for business users
- Intent classification and field extraction
- 5 validation controls for intent, required fields, product names, dates, and unsupported prompts
- End-to-end workflow from Snowflake data to AI-powered business output

## Architecture
User Question → OpenAI/LangChain Router → Validation Layer → Forecasting API → Snowflake/Model Output → Business Response

## Example Prompt
"What will be the demand for Product X in January 2025?"

## Resume Bullet
Solved the gap between Snowflake data and non-technical business users by designing an OpenAI/LangChain workflow that translated natural-language questions into structured API calls for price and demand forecasting.

Deployed 2 reusable FastAPI/uvicorn prediction services with 5 validation controls, showing how Snowflake-backed data products can support reliable AI workflows and executive decision-making.

## What I Learned
This project taught me that enterprise AI is not only about model performance. It is about connecting data, APIs, AI interfaces, validation, and business usability into one reliable workflow.
