version: 2.1

orbs:
    hello: circleci/hello-build@0.0.7 # uses the circleci/buildpack-deps Docker image

workflows:
    "Hello Workflow":
        jobs:
          - hello/hello-build
