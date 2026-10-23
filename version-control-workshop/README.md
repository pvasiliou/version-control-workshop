# Version Control Workshop Starter Project

An Eclipse Java project designed for a collaborative Git/GitHub workshop.

## Files

- `src/Main.java`: replace one uniquely assigned `GREETING_SLOT_XX` comment with `System.out.println("Hello from First Last");`. Edit **only** your assigned slot. 
- `src/ConflictDemo.java`: edit the `String message = "BASELINE";` line on two separate branches to demonstrate a merge conflict.
- `.project` / `.classpath`: Eclipse Java project metadata.
- `.gitignore`: excludes generated build output and local metadata.

## Import into Eclipse

1. Clone this repository through the Eclipse **Git Repositories** view.
2. Import the cloned project as an existing Eclipse project if it does not appear automatically.
3. Check that a JDK/JRE is configured and run `Main.java`. You should see the print statement in your console. 

## Greeting-slot rules

1. Create a new branch from `main`, for example `feature/greeting-ab`.
2. Replace exactly one uniquely assigned `GREETING_SLOT_XX` comment with a `System.out.println` line. You can add your name and surname.
3. Save, inspect the diff, stage the intended change, and commit with a descriptive message.
4. Push your feature branch. The integrator will merge branches into `main`.

The separator comments are intentional. Leave them unchanged.


