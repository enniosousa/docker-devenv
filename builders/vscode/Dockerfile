FROM codercom/code-server:latest


COPY ./extensions/ /extensions/
COPY ./settings.json /root/.local/share/code-server/User/settings.json
RUN code-server --install-extension /extensions/ms-azuretools.vscode-docker-1.12.1.vsix
RUN code-server --install-extension /extensions/felixfbecker.php-intellisense-2.3.14.vsix
RUN code-server --install-extension /extensions/onecentlin.laravel-extension-pack-1.0.0.vsix