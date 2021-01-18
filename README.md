# aruk

Another GTD App!

## Entities

```text
User:
    - email: `String`

Type: `Enum`
    Task
    Project

State: `Enum`
    Inbox
    Next
    Later
    Waiting
    Scheduled
    Someday
    Trash

Thing:
    - type: `Type`
    - state: `State`
    - parent: `Option<Thing>`
    - Owner: `Option<User>`
    - name: `String`
    - tags: `Vec<String>`
    - notes: `Vec<String>`
    - start date: `usize`
    - due date: `usize`
    - completed `usize`
```

## Technologies

### Frontend

VueJS + TypeScript + PWA + Vuetify

### Backend

#### business

Rust

#### api

Rust + PostgreSQL + tide (web)
