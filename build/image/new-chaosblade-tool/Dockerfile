FROM wangtong719/chaosblade-tool:1.7.3

ARG BLADE_VERSION=1.0.0

ENV CHAOSBLADE_HOME /opt/chaosblade
WORKDIR ${CHAOSBLADE_HOME}

COPY chaos_os ${CHAOSBLADE_HOME}/bin

ENV PATH ${CHAOSBLADE_HOME}:${PATH}
CMD ["sh", "-c", "tail -f /dev/null"]
