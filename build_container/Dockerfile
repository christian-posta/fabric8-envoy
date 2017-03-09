FROM centos:7
COPY ./build_container.sh /
RUN  ./build_container.sh
RUN export PATH=/opt/envoy_env/gcc-4.9.4/bin:$PATH && export CC=`which gcc` && export CXX=`which g++`
