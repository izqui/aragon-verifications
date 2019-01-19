# Aragon Verifications

## What’s this?

A simple crawler to parse all the signatures available in the [aragon membership thread](https://forum.aragon.org/t/aragon-cooperative-membership-thread/463) in order to showcase 
how many people had verified themselves.

## Tech stack

* ['create-next-app'](https://github.com/segmentio/create-next-app) 
* [yarn](https://yarnpkg.com/lang/en/docs/cli/create/)
* [styled components](https://www.styled-components.com/)
* [nightmare](https://github.com/segmentio/nightmare)
* [aragon-ui](https://github.com/aragon/aragon-ui)

### Test locally

```bash
yarn
yarn dev
```

```bash
now
```

### ToDo

* [] Integrate `keybase-verify` to actually confirm each individual PGP signature.
* [] Implement scrolling into Nightmare to fetch all posts or use a more sensible API
* [] Ignore repeated or poorly parsed posts.
* [] Make it less of an eye-sore.