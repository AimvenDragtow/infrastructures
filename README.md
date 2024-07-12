<a href="https://csorigins.com">
    <img src="https://avatars.githubusercontent.com/u/50500947">
</a>

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg

# Infrastructures

<!-- add badges -->

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/AimvenDragtow/infrastructures/deploy.yml)

![Uptime Robot status](https://img.shields.io/uptimerobot/status/m797202304-566b3b18c78c0d703e14004b)
![Uptime Robot ratio (30 days)](https://img.shields.io/uptimerobot/ratio/m797202304-566b3b18c78c0d703e14004b)

[![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/AimvenDragtow/infrastructures)

This repository contains the base infrastructure for debian-based servers. It is designed to use docker with Traefik as a reverse proxy. The repository is designed to be used with GitHub Actions for CI/CD.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Debian OS
- Docker
- Docker Compose

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/AimvenDragtow/infrastructures
   ```

2. Go to Traefik folder

   ```bash
   cd infrastructures/traefik
   ```

3. Create a `.env` file with the following content:

   ```bash
   TRAEFIK_DASHBOARD_USERS=user:realm:password
   ```

4. Run Traefik

   ```bash
   docker-compose up -d
   ```

## Contributing

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the CC BY-NC-ND 4.0 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements

- [Traefik](https://traefik.io/)
- [Docker](https://www.docker.com/)
- [GitHub Actions](https://docs.github.com/fr/actions)
- [Creative Commons](https://creativecommons.org/)
- [Contributor Covenant](https://www.contributor-covenant.org/)
- [All Contributors](https://allcontributors.org/)
