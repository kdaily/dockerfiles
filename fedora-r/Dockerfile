FROM fedora
RUN dnf -y install R-core R-core-devel
RUN Rscript -e 'install.packages("synapser", repos=c("https://sage-bionetworks.github.io/staging-ran", "http://cran.fhcrc.org"))'
