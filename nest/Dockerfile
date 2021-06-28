ARG VARIANT="16-buster"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

RUN mkdir -p /workspaces/nest
WORKDIR /workspaces/nest

COPY . /workspaces/nest

CMD ["npm", "run", "start"]
