# Bluefin Docs

These docs are pretty sparse on purpose as Bluefin's intended to be invisible. Ideally the docs should be able to be consumed in one sitting.

## Guidelines

- Docs linking to upstream documentation directly with a short summary is preferred.
- There's likely a reason why something is undocumented.

## Previewing your changes

You've made some changes and want to see how they look?

You can install jekyll and run it:

```
brew install ruby
gem install bundler
bundle install
jekyll serve
```

Then make sure to format all your files with Prettier!

```
just format
```

Alternatively, you can run the container:

```
docker compose up
```
