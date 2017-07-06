# docker solr legacy
[![](https://images.microbadger.com/badges/image/murny/docker-solr-legacy.svg)](https://microbadger.com/images/murny/docker-solr-legacy "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/murny/docker-solr-legacy.svg)](docker-solr-legacy "Get your own version badge on microbadger.com")
[![Build Status](https://travis-ci.org/murny/docker-solr-legacy.svg?branch=master)](https://travis-ci.org/murny/docker-solr-legacy)

Run Solr 5.4 using docker 

This is a backport to a legacy version of solr (5.4). As the official solr docker no longer supports any versions less then 5.5.

Majority of the code and everything else was stolen from https://github.com/docker-solr/docker-solr. See this repo for documenation and information.

## How to use this image
Pull down image: `docker pull murny/docker-solr-legacy`

Run the image, mapping your ports to your localmachine: `docker run -p 8983:8983 murny/docker-solr-legacy`

Open brower and navigate to `http://localhost:8983/solr`
