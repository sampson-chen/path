path
====

Path is the second iteration of [sack](https://github.com/sampson-chen/sack).

Unlike its predecessor, it shall refrain from being hundreds of lines of
shellscript.

What it does:
-------------

Path tags paths (file paths, URLs) to allow for rapid selection and
manipulation.

Features:
---------

- Tags paths
- Retrieve tagged paths
- CLI
- Supports Unix pipes

Status:
-------

*Design* | Prototype | Beta | Release

(TODO) What should be considered a path?
----------------------------------------

- Things that can be considered URLs (there is probably a library for this)
    - Uninterrupted block of text that start with {"http://", "https://", "www", ...}
- Things that can be considered file system paths (might be a library for this too!)
- Words that match names of files and folders in current working directory (though non-recursive, probably).
- What about forward slashes for Windows systems?

Other TODOs:
------------
- Describe what path should do in one sentence. Focus on building just that. It should do one thing and do it well.
- Feature list. Keep it small and relevant to core functionality. MVP.
- Design workflows and describe them as one would for a user-manual. If it's hard to describe, it's hard to use. Stay with "works-as-you-expect-it" conventions.
- Choose a language (Golang or Python)
- Map out architecture.
- Build it.
- Get feedback, iterate.
- (Future) sack-like support for tagging not just file paths, but search terms.
