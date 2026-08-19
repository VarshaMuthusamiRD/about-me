1. Revert all changes made by your immediately previous prompt. Restore the project to exactly the state it was in before your last changes. Do not modify, delete, or create anything else. First inspect the changes from your previous turn, then revert only those changes. Do not revert any changes that existed before your previous prompt.

- use /rewind

- it reverses all of the doings of last prompt to how the codebase was before the last prompt


2. C — Context, goal, constraints, acceptance criteria plus examples, but also point at an existing file and say "follow this pattern", and name two things that must not happen.

- provides the expected result with less to no questions.

3. resolving merge conflicts:

explain the conflict: what each side was trying to do, and what the options are and propose resolution

hand resolve the conflict i.e go manually and resolve it part by part. both functionalities should not be lost and common functionalities should be merged and maintained with the better version
 
4. commit multiple checkpoints

look at everything uncommitted and propose a set of atomic commits — one logical change each — along with the message for each, and to tell you if anything should not be committed. 

each commit message must say why along with what, be specific, under 72 characters, imperative mood, no trailing full stop, must not claim more than diff does.

5. write PR request

write to include what a reviewer actually needs: why this approach, what you considered and rejected, what is out of scope, and what you want them to look at hardest