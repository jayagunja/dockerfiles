ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    trainer="jayanthi G" \
    duration="120hrs"
ARG USERNAME=Jayanthi    
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]   