# Changelog

## v0.6.1

  * Fixes
    * Builds using the musl C library now

## v0.6.0

  * New features
    * Support setting unique hostnames per board

## v0.5.3

  * New features
    * Works with exrm now

  * Fixes
    * Only hang on exit if unintentional
    * Mount /run; clean up other mounts
    * Use first boot file if multiple are found
    * HOME environment variable is /root now so that it is possible to mount a
      writable filesystem there and use it

## v0.4.6

  * Fixes
    * Address issues found with Coverity
