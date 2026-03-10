FROM rocker/shiny:4.3.1

RUN R -e "install.packages(c('shiny','tidyverse','DT'), repos='https://cloud.r-project.org')"

COPY app1 /srv/shiny-server/app1
COPY app2 /srv/shiny-server/app2
COPY app3 /srv/shiny-server/app3
