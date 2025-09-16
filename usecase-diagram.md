```markdown
```mermaid
%%{ init : { "theme" : "default" } }%%
%%{ init: { "themeVariables": { "actorTextColor": "#ff0000", "useCaseTextColor": "#ffcc00" }}}%%
%%{ init : { "theme" : "default" } }%%
  usecaseDiagram
    actor Student
    actor Admin
    Student --> (Register for Course)
    Student --> (Drop Course)
    Admin --> (Add Course)
    Admin --> (Remove Course)
    Admin --> (View Registrations)
    (Register for Course) --> (Check Prerequisites)
    (Drop Course) --> (Confirm Drop)
```
