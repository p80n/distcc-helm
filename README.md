# distcc Helm Chart
Helm chart to install [distcc](https://github.com/distcc/distcc).

distcc -- a free distributed C/C++ compiler system


## TL;DR;

```bash
helm repo add p80n-distcc https://p80n.github.io/distcc-helm/
helm repo update
helm upgrade --install distccd --namespace distccd distccd p80n-distcc/distcc

```

## Introduction

I run Gentoo Linux, so I need distcc :D
