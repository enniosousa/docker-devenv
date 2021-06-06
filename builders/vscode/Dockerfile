FROM codercom/code-server:latest

COPY ./settings.json /root/.local/share/code-server/User/settings.json
USER root
RUN code-server --install-extension ms-azuretools.vscode-docker
RUN code-server --install-extension felixfbecker.php-intellisense
RUN code-server --install-extension onecentlin.laravel-extension-pack
