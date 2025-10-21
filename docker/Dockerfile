FROM ubuntu:noble

RUN apt-get update &&                               \
    apt-get install -y                              \
                    --no-install-recommends         \
                    --no-install-suggests           \
                                                    \
                    ghostscript                     \
                    make                            \
                    fonts-liberation                \
                    latexmk                         \
                    texlive-xetex                   \
                    texlive-lang-english            \
                    texlive-lang-cyrillic           \
                    texlive-fonts-recommended       \
                    texlive-extra-utils             \
                    python3 python3-pip

RUN pip3 install --break-system-packages pdfly
