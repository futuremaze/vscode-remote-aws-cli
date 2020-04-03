#-------------------------------------------------------------------------------------------------------------
# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License. See https://go.microsoft.com/fwlink/?linkid=2090316 for license information.
#-------------------------------------------------------------------------------------------------------------

# To fully customize the contents of this image, use the following Dockerfile instead:
# https://github.com/microsoft/vscode-dev-containers/tree/v0.106.0/containers/alpine-3.10-git/.devcontainer/Dockerfile
FROM amazon/aws-cli
# ** [Optional] Uncomment this section to install additional packages. **
#
# RUN apk update \
#     && apk add --no-cache <your-package-list-here>

# The following packages are required to install vs-code-server running on conntainer
RUN yum -y install tar gzip

WORKDIR /aws
ENTRYPOINT [ "/bin/bash" ]
