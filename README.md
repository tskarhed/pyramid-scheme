# pyramid-scheme

Pyramid scheme as a social/economical experiment, based on fake money. Should also contain simulations of pyramid schemes.

## Idea

Let's introduce a fake currency `jaja (Я)`, from the famous Icelandic song ["Jaja Ding Dong"](https://www.youtube.com/watch?v=7anGdjnklEo).

You get to join the pyramid scheme via an invite, and a cost of `10 jajas`. You earn `jajas` by inviting new members, from which you get a 50% (?)(Requires you to recruit 2 to break even) cut.

## Features

- Login via Facebook/Google/Twitter/Whatever
  - The signup process should be one-click
  - No personal data will be saved, just enough for the authentication
- Character creation
  - You get a random name that you might possibly change
  - You can use character creation with [TL-GAN](https://github.com/SummitKwan/transparent_latent_gan) to generate a profile picture
- Pyramid network
  - You can visualize the entire pyramid scheme and every node
  - You can easily see how much you've earned
  - Make this a practice in graph databses such as Neo4js, maybe?
- Publically available data
  - If someone wants to use the data, make it easy to export
- Sell it as a obvious pyramid scheme for people who always wanted to be in a pyramid scheme