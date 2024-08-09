# Gptscript with Supabase API

Welcome to the Gptscript project! This guide will help you understand how to use Gptscript to interact with Supabase APIs.

## Overview

Gptscript is a friendly assistant designed to help you with DevOps-related tasks using CLI programs. In this project, Gptscript is configured to assist with Supabase API operations.

## Prerequisites

Before you begin, ensure you have the following:

- [Supabase API key](https://supabase.com/docs/reference/api/introduction)

### Available Tools

- **Read Operations:**

  - File: `read-only/tool.gpt`
  - Description: Helps with read operations in Supabase API.
  - Tools: `v1-get*`, `v1-list*` from `openapi.yaml`.

- **Read-Write Operations:**

  - File: `read-write/tool.gpt`
  - Description: Helps with read and write operations in Supabase API.
  - Tools: All the tools from `openapi.yaml`.
