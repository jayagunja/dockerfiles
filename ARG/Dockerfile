ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    trainer="jayanthi G" \
    duration="120hrs"
ARG USERNAME=Jayanthi
# accessing args value in container also by setting ENV    
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]   