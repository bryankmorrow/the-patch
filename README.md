![alt tag](img/pumpkin.png?raw=true "the-patch")

The Patch
====

This repo contains a collection of sampe policies and reporting templates.<br/>
Each directory contains policies and reports specific to containers, dockerfiles, etc.<br/><br/>

Here are a few examples. Full docs available at <a href="about.g3t.dev">about.g3t.dev</a>

Examples

Container:<br/>

```
$ ghost --rego-file ghost.rego  --format template --template @ghost.tpl -o report.html --ignore-unfixed nginx:latest
```

Dockerfile:<br/>

```
ghost df --rego-file dockerfile/df.rego Dockerfile-bad 
```