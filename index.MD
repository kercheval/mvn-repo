---
layout: default
title: Maven Repository for kercheval.org
github: https://github.com/kercheval/mvn-repo
---

# Maven Repository for kercheval.org

***

<span class="credits left">Project maintained by <a href="https://github.com/kercheval">kercheval</a></span>
<br/><br/>

This repository has been setup to host kercheval.org projects.  This
is a github gh_pages branch dedicated to the deployment of projects to
allow the simple deployment and recovery of project artifacts.

The base URL for the repository is

http://kercheval.org/mvn-repo/

Snapshots are stored in the snapshot directory and releases are in the releases directory.

A typical gradle usage of this repository for a plugin might be

buildscript {<br/>
    repositories {<br/>
        mavenRepo url: 'http://kercheval.org/mvn-repo/releases'<br/>
    }<br/>
    dependencies {<br/>
        classpath 'org.kercheval:GradleCMPlugin:+'<br/>
    }<br/>
}

This repository should be usable by standard maven interactions.

