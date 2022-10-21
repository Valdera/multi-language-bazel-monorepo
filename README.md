# Bazel Monorepo Tutorial

Run test on a project

```
bazel test projects/calculator/...
```

Run project

```
bazel run projects/my-python-app:main
```

Build projects

```
bazel build //...
```

Trace dependencies

```
bazel query @com_github_gorilla_mux//...
```

Add package with yarn

```
bazel run @yarn//:yarn -- add <package>
```
