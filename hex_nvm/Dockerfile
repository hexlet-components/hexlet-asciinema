FROM hex/base

RUN sudo rm /bin/sh && sudo ln -s /bin/bash /bin/sh

RUN wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.37.2/install.sh | bash
RUN source ~/.nvm/nvm.sh && nvm install --lts && nvm install-latest-npm
