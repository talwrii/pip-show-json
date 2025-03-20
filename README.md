# pip-show
Show JSON metadata about a pip package.

# Motivation
Pip used to have facilities to show metadata about packages with `pip show` as well as search  with `pip search`. This functionality was disabled due to [load issues](https://discuss.python.org/t/pip-search-is-still-broken/18680).

This is basically a wrapper around `curl https://pypi.org/pypi/$PACKAGE/json` but it is easy to discover.

I imagine `pip show` should be changed to use this API. But my expectation is that a patch for this would sit around for a couple of years and I get a distinctly "stop complaining vibe" from the discussion above. So I'll just create a work around and if people use it then it might eventually get merged.

# About me
I am @readwithai. I sometimes make [productivity tools](https://readwithai.substack.com/p/my-productivity-tools) similar to this. I also am making [tools for reading](https://readwithai.substack.com) sometimes with [Obsidian](https://readwithai.substack.com/p/what-exactly-is-obsidian).

If any of this sounds interesting you can follow me on [X](https://x.com/readwithai) or my [blog](https://readwithai.substack.com).
