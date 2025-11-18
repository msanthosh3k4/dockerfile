ARG version
FROM almalinux:${version:-9}
ENV course="Devops" \
    trainer="santhosh" \
    duriation="120"
ARG USERNAME=SANTHOSH
RUN echo "hello user is ${USERNAME}" > /tmp/dev.txt
CMD ["sleep","100"]