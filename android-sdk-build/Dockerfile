FROM cab404/docker-android-sdk:bare

ARG TOOLS_VERSION=27.0.3
ARG SDK_VERSION=27

RUN sdkmanager \
### LIST PACKAGES TO INSTALL HERE ###
    'platforms;android-'$SDK_VERSION \
    'platform-tools' \
    'build-tools;'$TOOLS_VERSION \
;
