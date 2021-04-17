### Local setup

Follow running slate here: https://github.com/slatedocs/slate/wiki/Using-Slate-in-Docker
Edit index.html.md in source to make changes to the api.
Once the changes have been updated on the master branch and all pipeline checks have passed - run the './deploy.sh' script from your terminal for the changes to be deployed to GH pages.

command:
`docker run --rm --name slate -p 4567:4567 -v $(pwd)/source:/srv/slate/source slatedocs/slate serve`

<!-- DEPLOYMENT INSTRUCTIONS
To Deploy any changes - Make the changes in the master branch, commit them and push to the repository and wait for all the tests to pass. Then run the './deploy.sh' command from your local terminal and go to the Docs Link to see the changes.  -->

<p align="center">
  <!-- <img src="https://raw.githubusercontent.com/slatedocs/img/main/logo-slate.png" alt="Slate: API Documentation Generator" width="226"> -->
  <br>
  <a href="https://github.com/slatedocs/slate/actions?query=workflow%3ABuild+branch%3Amain"><img src="https://github.com/slatedocs/slate/workflows/Build/badge.svg?branch=main" alt="Build Status"></a>
  <a href="https://hub.docker.com/r/slatedocs/slate"><img src="https://img.shields.io/docker/v/slatedocs/slate?sort=semver" alt="Docker Version" /></a>
</p>

<p align="center">Conscent Developer Documentation - take a look at our beautiful, intelligent and responsive API documentation.</p>

<p align="center"><img src="https://raw.githubusercontent.com/slatedocs/img/main/screenshot-slate.png" width=700 alt="Screenshot of Example Documentation created with Slate"></p>

<p align="center"><em>The documentation above was created with the help of Slate. Check it out at <a href="https://slatedocs.github.io/slate">slatedocs.github.io/slate</a>.</em></p>

## Contributors

Slate was built by [Robert Lord](https://lord.io) while at [TripIt](https://www.tripit.com/). The project is now maintained by [Matthew Peveler](https://github.com/MasterOdin) and [Mike Ralphson](https://github.com/MikeRalphson).

Thanks to the following people who have submitted major pull requests:

- [@chrissrogers](https://github.com/chrissrogers)
- [@bootstraponline](https://github.com/bootstraponline)
- [@realityking](https://github.com/realityking)
- [@cvkef](https://github.com/cvkef)

Also, thanks to [Sauce Labs](http://saucelabs.com) for sponsoring the development of the responsive styles.
