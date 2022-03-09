# Testkube Tests Run

## **Synopsis**

Starts a new test based on the Test Custom Resource name and returns the results to the console.

```
testkube tests run <testName> [flags]
```

## **Options**

```
      --args stringArray       Executor binary additional arguments.
  -a, --download-artifacts     Download artifacts automatically.
      --download-dir string    Download directory. (default "artifacts")
  -h, --help                   Help for run.
  -n, --name string            Execution name, if empty will be autogenerated.
  -p, --param stringToString   Execution envs passed to executor (default []).
      --params-file string     Params file path, e.g. postman env file - will be passed to executor if supported.
  -f, --watch                  Watch for changes after start.
```

## **Options Inherited from Parent Commands**

```
      --analytics-enabled    Enable analytics (default "true").
  -c, --client string        Client used for connecting to testkube API one of proxy|direct (default "proxy").
      --go-template string   When choosing output==go, pass golang template (default "{{ . | printf \"%+v\"  }}").
  -s, --namespace string     Kubernetes namespace (default "testkube").
  -o, --output string        Output type - raw, json or go  (default "raw").
  -v, --verbose              Show additional debug messages.
```

### SEE ALSO

* [Testkube Tests](testkube_tests.md)	 - Tests management commands.
