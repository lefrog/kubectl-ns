# kubectl-ns

Simple kubectl wrapper to ease passing of namespace.

## Usage

Simply copy this script in your local bin directory (e.g. ./local/bin) and make symbolic line of it
with the desired namespace as the extension.
e.g.
```
ln -s kubectl-ns kubectl.foo
```

Now when you invoke `kubectl.foo get pod` it will automatically add `--namespace=foo` to the kubectl command.
 