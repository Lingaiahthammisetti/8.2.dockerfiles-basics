# ARG version
# FROM almalinux:${version}
# CMD ["sleep", "100"]


# ARG version
# FROM almalinux:${version}
# RUN cat /etc/*release
# CMD ["sleep", "100"]

ARG version
FROM almalinux:${version:-8}
ARG COURSE=Docker
ARG TRAINER=Sivakumar
ARG Duration=120Hrs
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${Duration} "
CMD ["sleep", "100"]