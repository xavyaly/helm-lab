# helm-lab

[Link](https://helm.sh/docs/)
[UTube](https://www.youtube.com/watch?v=3HqLVgteMrQ)

# Install helm
```
$ brew install helm
Running `brew update --auto-update`...
==> Auto-updated Homebrew!
Updated 3 taps (weaveworks/tap, homebrew/core and homebrew/cask).
==> New Formulae
bazel-remote
==> New Casks
json-viewer

You have 8 outdated formulae and 1 outdated cask installed.

Warning: helm 3.12.3 is already installed and up-to-date.
To reinstall 3.12.3, run:
  brew reinstall helm
```

# HELM version
```
$ helm version
version.BuildInfo{Version:"v3.12.3", GitCommit:"3a31588ad33fe3b89af5a2a54ee1d25bfe6eaa5e", GitTreeState:"clean", GoVersion:"go1.20.7"}
```


```
$ helm create todo-api
Creating todo-api
```

```
$ cd todo-api/
```

```
$ ls -l
total 16
-rw-r--r--@  1 javedalam  staff  1144 Aug 25 19:47 Chart.yaml
drwxr-xr-x@  2 javedalam  staff    64 Aug 25 19:47 charts
drwxr-xr-x@ 10 javedalam  staff   320 Aug 25 19:47 templates
-rw-r--r--@  1 javedalam  staff  1875 Aug 25 19:47 values.yaml
```