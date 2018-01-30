FROM cab404/docker-android-sdk:bare

ARG TOOLS_VERSION=27.0.3
ARG SDK_VERSION=27

RUN sdkmanager \
### LIST PACKAGES TO INSTALL HERE ###
    'platforms;android-'$SDK_VERSION \
    'platform-tools' \
    'add-ons;addon-google_apis-google-24' \
    'build-tools;'$TOOLS_VERSION \
;
