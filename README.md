# wgtwoapis-openapi
The openapi part of wgtwoapis.

See also https://github.com/working-group-two/wgtwoapis

## Documentation
See https://docs.wgtwo.com


## Setup required to release/deploy from local machine:

See [our internal wiki](https://github.com/omnicate/loltel/wiki/Public-APIs#releasing-to-the-maven-central-repository) for the required local tooling/setup for releasing to the maven central repository.

## Releasing java/maven artifacts

See also the readme in [wgtwoapis](https://github.com/working-group-two/wgtwoapis) for
advanced instructions.

1. `./mvnw build-helper:parse-version release:prepare -B`
2. `./mvnw release:perform`

## Protobuf/buf/go release

Not applicable for this repository.
