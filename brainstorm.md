# Brainstorm
## Basic idea
NPC interaction in games hasn't really been pushed beyond basic numbered dialog options and canned response. Is it possible to make a character with a basic personality and memories that can be interacted with in more nuanced ways. This is an exploration of this concept. The idea is to connect something like this to natural language processing and outputs.

## Who is the character.
- short stories from the character's life.
    - traumatic experiences from childhood.
    - what is relationship with parents.
    - what was early childhood like, friends, school, etc
- what is character doing now.
    - does the character feel fulfilled?
- what are character's goals.
    - what is holding character back from achieving goals.
- does the character know the player?
- is the context in which the player is interacting with the character making normal sense?
- does the player introduce themselves to the player?
- does the character understand what the player is saying?

-------------
## Approach ideas
Example scenario: Player approaches character in town and speaks. **If** player is known to Character through previous interaction **and** **if** the player says something that makes sense they will respond according to how the outcomes of previous interactions went. Depending on that character's natural disposition, owing to a variety of factors including upbringing.


## Implementation
Character will be an object with defined personality traits, canned catch phrases, a general mood or disposition or a probability of being in a certain mood. Different events in the world also effect character mood and disposition and their feelings towards the character.