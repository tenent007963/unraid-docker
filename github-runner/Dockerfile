FROM tenent007963/github-runner:latest
ENV RUNNER_ALLOW_RUNASROOT=1
WORKDIR /actions-runner
CMD ./config.sh --url $URL --token $TOKEN && ./run.sh