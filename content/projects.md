+++
title = "Projects"
date = "2017-09-27"
tags = []
categories = []
draft = false
+++

Here are some of the open source projects that I am involved with.

## OpenShift - https://openshift.com
Since 2012 I have had the good fortune to work on the OpenShift platform, first as an engineer and currently as an engineering manager. We originally thought of OpenShift as a [Platform-as-a-Service](https://en.wikipedia.org/wiki/Platform_as_a_service) system, but this is almost overly limiting. The current incarnation of OpenShift, based on [Linux Containers](https://www.opencontainers.org) and Google's [Kubernetes](https://kubernetes.io) system, represents an entire ecosystem of tools for development, deployment, and management of cloud-native software.

* Source: https://github.com/openshift/origin
* Releases: https://github.com/openshift/origin/releases
* Container: https://hub.docker.com/r/openshift/origin/
* Minishift all-in-one environment: https://www.openshift.org/minishift/

## AsciiBinder - http://asciibinder.org
In 2014, during my rotation as the OpenShift Origin tech lead (for v2), I helped the OpenShift documentation team migrate from [PressGang](http://pressgang-ccms.github.io) to a text-file based approach to product documentation. Our system relied on [git](https://git-scm.com), text files written in the [AsciiDoc](http://asciidoc.org) markup format, and [Asciidoctor](http://asciidoctor.org), a powerful utility for transforming AsciiDoc-based files into HTML or PDF output.

The utility that I wrote caught the attention of docs teams outside of OpenShift. In 2015 a developer associated with one of those groups helped me to formalize my code into an open source project called AsciiBinder.

* Source: https://github.com/redhataccess/ascii_binder
* Releases: https://rubygems.org/gems/ascii_binder
* Container: https://hub.docker.com/r/projectatomic/ascii_binder/
* Real-World Use: https://github.com/openshift/openshift-docs

## SWN Sector Generator - http://swn.emichron.com
One of my proudest and nerdiest programming accomplishments is this game aid for a tabletop roleplaying game called [Stars Without Number](http://www.sinenomine-pub.com/?page_id=395). The game author produced an amazing set of rules for randomly creating a whole sector of space - star systems, planets, alien races - the works. This tool enables users to randomly generate one of these sectors and then download it as an all-in-one-page wiki.

* Source: https://github.com/nhr/swn
* Container: https://hub.docker.com/r/nhripps/swn/

## Talks and Articles

* "That App You Love" series at developers.redhat.com: http://red.ht/2xOMaHo
* "That App You Wrote" talk from DevConf.cz 2017: https://www.youtube.com/watch?v=DfkNqW1L4FA
