# loggen
a script to generate logfiles.

## Why?
This was built as part of an interview coding challenge.

We needed to generate logs of varying size that wouldn't be trivially compressed by the log transport and storage systems, so we rubbed some /dev/random on it.

It turns out that /dev/random is pretty slow. This got the job done, but wasn't nearly as fast as we needed.

It must've been alright though, they offered me the job. :)
