# Infrastructure Overview
This application is a standalone React app that uses hooks for state management. It has a simple API for managing a list of items.

## Data Models
- **Item**: Represents an item with `id` (number) and `name` (string).

## API Design
- **GET /api/items**: Returns a list of items.
- **POST /api/items**: Accepts a JSON object to create a new item.
- **DELETE /api/items/:id**: Deletes an item based on the provided ID.

## Key Decisions
- Using React Hooks for state management to demonstrate modern React practices.
- Local storage for persistence of the item list.