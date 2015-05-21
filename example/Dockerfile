FROM mattaitchison/alpine-mono


COPY test.cs /
RUN mcs test.cs
CMD ["mono", "test.exe"]
