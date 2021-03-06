# harcap - Capture HAR/trace/screenshot/filmstrip on CLI

This is a tool to capture HAR and various outputs from given website.
In addition to various capture features, it also has a feature to inject a delay for specified resource(s).
This can be used to pinpoint a bottleneck of a page, by analyzing result of multiple measurements.

# Usage
```
$ ./bin/harcap.js -h
Usage: harcap [options]

Options:
  -V, --version             output the version number
  -C, --chrome <arg>        Pass arg to Chrome (default: [])
  -D, --debug <level>       Set debug level (default: 0)
  -H, --header <header>     Add header (default: {})
  -L, --headless            Run headless
  -T, --timeout             Timeout
  -c, --cache               Enable caching
  -d, --delay <ms>:<expr>   Apply delay to matching URL (default: [])
  -e, --endpoint <url>      Connect to given websocket endpoint
  -f, --fullpage            Take fullpage screenshot
  -i, --interval <ms>       Screenshot capture interval (default: 0)
  -m, --model <help|model>  Emulate device (ex: iPhone 6)
  -n, --warmup <N>          Fetch page N-times before measurement (default: 0)
  -o, --outfile <har>       HAR file to save
  -s, --screenshot <image>  Save screenshot (ex: image-%d.jpg)
  -t, --trace <tracelog>    Capture trace log
  -v, --verbose             Verbose message output
  -h, --help                output usage information
  ```
