CHANGELOG
=========

1.2.2
-----

* compatibility with Symfony 3.0 components

1.2.1
-----

This release is the same as `1.2.0` as the tag was created on the wrong
commit hash.

1.2.0
-----

* added API method to only delete the source file from the storage

1.1.1
-----

* update installation instructions regarding the BC break introduced in 1.1.0

1.1.0
-----

* ignore additional properties that are not reflected in the model classes
  during deserealisation

* additional options (a list of profiles to be used, a custom path format a
  payload) can be passed to the methods ``CloudInterface::encodeVideoByUrl()``
  and ``ClientInterface::encodeVideoFile()``

* added a payload property to the ``Video`` model (by @tgallice in #2)
