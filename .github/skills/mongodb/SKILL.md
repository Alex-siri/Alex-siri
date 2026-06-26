---
name: mongodb
description: 'Use when working with MongoDB databases, schemas, queries, aggregation pipelines, indexes, Mongoose models, or Atlas connections.'
argument-hint: 'task, database, collection, or query goal'
---

# MongoDB

## When to Use
- Query, filter, update, or delete MongoDB documents
- Design collections, fields, and indexes
- Build aggregation pipelines or troubleshoot them
- Work with MongoDB Atlas or Mongoose-based apps

## Procedure
1. Identify the driver or library in use, such as the native MongoDB driver or Mongoose.
2. Confirm the collection shape, field types, and any relevant index constraints.
3. Choose the simplest operation that satisfies the request: find, update, aggregate, or migrate.
4. Prefer targeted queries and explicit projections to avoid unnecessary document reads.
5. Validate the result against the expected documents, edge cases, and performance impact.

## Notes
- Use aggregation only when a basic query cannot express the logic cleanly.
- Prefer compound indexes for common filter-and-sort patterns.
- Keep schema changes backward compatible when the data already exists.