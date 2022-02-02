FROM ubuntu:18.04

ENV PATH="/snpEff/scripts:${PATH}"

RUN apt-get update && apt-get install -y \
    openjdk-8-jdk \
    unzip \
    wget

RUN wget --no-check-certificate -O snpEff_v4_3t_core.zip https://sourceforge.net/projects/snpeff/files/snpEff_v4_3t_core.zip/download && \
    unzip snpEff_v4_3t_core.zip && \
    chmod 777 /snpEff/scripts/* && \
    rm snpEff_v4_3t_core.zip

    


