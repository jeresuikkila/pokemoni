# Pokemoni

A study in Typescript and React using the classic Pokemon card game as the basis.

## Development

### TODO

- Decks <https://github.com/PokemonTCG/pokemon-tcg-data/tree/master/json/decks>
- Maps <https://bitbucket.org/coreyog/materialpokedex/src/master/>

### Storybook

Storybook is setup for component development independent of the application following the instructions at:
<https://www.learnstorybook.com/react/en/get-started/>

`npx -p @storybook/cli sb init`

Also add the knobs addon as instructed at <https://www.learnstorybook.com/react/en/addons/>

To host the static version of Storybook

```sh
npm run build-storybook
docker run --name taskbox-storybook -d -p 8080:80 -v $(pwd)/storybook-static:/usr/share/nginx/html:ro nginx
```

## Acknowledgements

Pokemon card images and deck data from <https://github.com/PokemonTCG>, <https://docs.pokemontcg.io/>
Map ideas and other inspiration <https://bitbucket.org/coreyog/materialpokedex/src/master/>
