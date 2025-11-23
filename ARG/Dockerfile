ARG version
FROM almalinux:${version:-9}
ENV course="Devops" \
    trainer="santhosh" \
    duriation="120"
ARG USERNAME=SANTHOSH
ENV USERNAME=$US
RUN echo "hello user is ${USERNAME},image version is ${version}" > /tmp/dev.txt
CMD ["sleep","100"]