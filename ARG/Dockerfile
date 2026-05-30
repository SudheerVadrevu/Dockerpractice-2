ARG version
FROM almalinux:${version:-9.5}
ARG sudheer=topper
ARG vineela=duller
RUN echo "sudheer is ${sudheer} and vineela is ${vineela} "
CMD [ "sleep", "100" ]


# How can you check version of your OS? cat /etc/*release
# almalinux:${version:-9.5} Here {version:-9.5} this syntax will be applicable for OS versions
# If you use ARG in other than versions then this syntax will not be applicable