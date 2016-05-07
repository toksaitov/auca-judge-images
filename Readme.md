auca-judge-images
=================

*auca-judge-images* is a repository of build and test images for different
programming languages and environments for use by the *auca-judge* system.

All images use [auca-judge-agent](https://github.com/toksaitov/auca-judge-agent)
to control build and test tasks remotely.

## Prerequisites

* *Docker*, *Docker Compose* `>= 1.11`, `>= 1.7.0`

## Usage

First, you need to build [auca-judge-agent](https://github.com/toksaitov/auca-judge-agent)
under the tag `toksaitov/images:auca-judge-agent`.

```bash
git clone https://github.com/toksaitov/auca-judge-agent.git
cd auca-judge-agent

docker build --tag="toksaitov/images:auca-judge-agent" .
```

Then, execute `docker-compose build` to build all local images.

## Licensing

All files in the following repository are licensed under the MIT license. See
LICENSE for the full license text.

## Credits

*auca-judge-images* was created by [Dmitrii Toksaitov](https://github.com/toksaitov).
