# [Choice] Ruby version (use -bullseye variants on local arm64/Apple Silicon): 3, 3.1, 3.0, 2, 2.7, 2.6, 3-bullseye, 3.1-bullseye, 3.0-bullseye, 2-bullseye, 2.7-bullseye, 2.6-bullseye, 3-buster, 3.1-buster, 3.0-buster, 2-buster, 2.7-buster, 2.6-buster
ARG VARIANT=sieger1x2/ruby:3.1_20.04
FROM sieger1x2/ruby:3.1_20.04

# Install Rails
# RUN gem install rails webdrivers rubocop solargraph htmlbeautifier

# Default value to allow debug server to serve content over GitHub Codespace's port forwarding service
# The value is a comma-separated list of allowed domains 
# ENV RAILS_DEVELOPMENT_HOSTS=".githubpreview.dev"

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment this line to install additional gems.
# RUN chown -R vscode:vscode /workspace/storage
# RUN chown -R vscode:vscode /workspace/logs
# RUN chown -R vscode:vscode /workspace/node_modules
# RUN chown -R vscode:vscode /usr/local/bundle
# RUN chown -R vscode:vscode /workspace/tmp/cache
# RUN chown -R vscode:vscode /workspace/public/packs
# RUN chown -R vscode:vscode /usr/local/hist
# RUN chown -R vscode:vscode /home/vscode

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1
