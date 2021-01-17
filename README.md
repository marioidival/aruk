# aruk
Another GTD App!


## Entidades

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
    - Owner: `User`
    - name: `String`
    - tags: `Vec<String>`
    - notes: `Vec<String>`
    - start date: `DateTime`
    - due date: `DateTime`
    - completed `DateTime`
        (é um campo data, mostrando quando acabou)


## Tecnologias

### Frontend

VueJS + TypeScript + PWA + Vuetify