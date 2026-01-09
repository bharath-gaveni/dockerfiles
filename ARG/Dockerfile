ARG VERSION
FROM almalinux:${VERSION:-9}
ARG course="k8" \
    duration="3months"
ENV course = ${course}    
RUN echo "course: ${course} , duration: ${duration} , version: ${VERSION}"
CMD ["sleep", "1000"]
