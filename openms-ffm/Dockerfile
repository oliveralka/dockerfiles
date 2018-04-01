FROM hroest/openms-lib-nightly

WORKDIR /openms-build

# make OpenMS all
RUN make FeatureFinderMetabo

WORKDIR /

# set path to OpenMS
ENV PATH="/openms-build/bin/:${PATH}"
