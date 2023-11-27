## TTTMeetUp

Presented in The Test Trbe 30th Bangalore Meetup on 25th Nov, 2023.

Link to the slides - https://www.slideshare.net/DimpyAdhikary/advanced-api-mocking-techniques

### Installation Guide for wirmock:
- Standalone jar https://wiremock.org/docs/download-and-installation/
- State Extension - https://github.com/wiremock/wiremock-state-extension

mapping folder - Contains wiremock request/rensponse mapping files \
__files filder - Contains response json files\
thunder_client_collection - Contains demo collection file to run the mocked end points

### How to Run the wiremock Server:
java -cp "wiremock-state-extension-standalone-<version>.jar:wiremock-standalone-<version>.jar" -jar wiremock-standalone-<version>.jar --global-response-templating
