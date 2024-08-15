# This Dockerfile is used to build aeon when launching binder.
# Find out more at: https://mybinder.readthedocs.io/en/latest/index.html

# Load jupyter python 3.11 image
FROM jupyter/scipy-notebook:python-3.11

# Set up user to avoid running as root
ARG NB_USER=user
ARG NB_UID=1000
ENV USER ${NB_USER}
ENV HOME /home/${NB_USER}

# Binder will automatically clone the repo, but we need to make sure the
# contents of our repo are in the ${HOME} directory
COPY . ${HOME}
USER root
RUN chown -R ${NB_UID} ${HOME}

# Switch user and directory
USER ${USER}
WORKDIR ${HOME}

# Install aeon based on master branch
RUN pip install --upgrade pip --no-cache-dir
RUN pip install -U "aeon[binder] @ git+https://github.com/aeon-toolkit/aeon.git@main"
