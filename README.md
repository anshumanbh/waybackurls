# waybackurls

Accept line-delimited domains on stdin, fetch known URLs from the Wayback Machine for `*.domain` and output them on stdout.

Usage example:

```
▶ cat domains.txt | waybackurls > urls
```

Install:

```
▶ go get github.com/tomnomnom/waybackurls
```

## Running the Docker image
`docker run -it abhartiya/tools_waybackurls -target anshumanbhartiya.com -result /tmp/waybackurls.txt`

## Credit

This tool was inspired by @mhmdiaa's [waybackurls.py](https://gist.github.com/mhmdiaa/adf6bff70142e5091792841d4b372050) script.
Thanks to them for the great idea!
