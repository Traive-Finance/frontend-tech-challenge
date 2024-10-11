# Introduction

Hello, fellow dev, how is it going? I hope you're doing fine. To continue our Job Application Process, you will need to be responsible for the next awesome app the world will see. For that, we are going to provide some context on how it will be built and which features it will possess.

# App Overview

Rick and Morty gathered all their TV show crew and decided that they would participate in the next Pokémon Tournament, and it's our responsibility to help them achieve their Pokémon Champion dream, after all, who doesn't want to be the “very best”?

We will play an important role in this process since we will build software that will help them find the perfect Pokémon combination for all of them. So, our app will support them with:

- [ ] The poke-trainers list: The List of all Rick and Morty's characters.
- [ ] The poke-trainer profile: The profile of each character and their favorite Pokémon.
- [ ] The poke-arena: A training battle simulator.

## The poke-trainers list!

This feature will consist of a list of all the characters from Rick and Morty's universe. But don't worry; we have some user stories to guide you through the requirements.

- [ ] As a **user**, I want to **be able to see a page of live characters** so I can **access their profile**.
- [ ] As a **user**, I want to **be able to search a character by name** so I can **access their profile more easily.**
- [ ] As a **user**, I want to **be able to see other pages of live characters** so I can **access all the live characters**.

## The poke-trainer profile!

It's important that we know more information about the poke-trainer we're analyzing so we can provide more assertive information when creating their Pokémon team.

- [ ] As a **user**, I want to **be able to see the character's profile**, so I **can have access to complete information about them.**
- [ ] As a **user**, I want to **be able to see the character's favorite Pokémon in the profile**, so I **can try to add him to their team.**

## The poke-arena!

Lastly, we need to provide a way for them to simulate their battles. In that case a few more user stories might help you out.

- [ ] As a **user**, I want to **be able to start a practice battle between 2 trainers from the list**, so I **can simulate their results.**
- [ ] As a **user**, I want to **be able to see a battle with 6 random Pokémons for each trainer**, so I **can find their best combination.**
- [ ] As a **user**, I want to **be able to see a detailed result of the battle** so I **can identify strong Pokémon picks.**

Now let’s understand how a battle works.

### Time to battle!

In a Pokémon battle, we have 6 Pokémon for each side, and they battle in a combined way that one Pokémon battles against **one Pokémon only.** These individual battles are defined by the Pokémon's **types**.

As far as we know, every Pokémon has at least _one_ **type** associated, and some types are more effective against others (which does double the damage). So every time a Pokémon's type is effective against another Pokémon's type (check one by one against all) they score **1 point**.

At the end of the battle, the Pokémon that has the most points wins (draws are allowed) scoring **1 point** for the **team**.

The team that has more points wins (draws are allowed).

# Tech Stuff

This project was settled with React + Typescript + Vite and to be able to start developing you need to `npm install` the dependencies.

After that run the project by running the command `npm run dev` and access it visiting [localhost](http:localhost:5173).
The API's that you will need can be found in:

- [PokéAPI](https://pokeapi.co/)
- [The Rick and Morty API](https://rickandmortyapi.com/)

# In Summary

I know that are some questions to ask, right? What should I display in the champs list? What should I display in the champ profile? But don't worry, as an engineer, we trust you will follow your gut and think about what is best for the product, and we can align on how you decided things when reviewing it together.

We wish you a happy journey and see you soon!
