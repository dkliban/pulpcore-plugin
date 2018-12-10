============================
Plugin API 0.1 Release Notes
============================

The Plugin API is not yet declared as stable. Backwards incompatible changes might be made until
stable version 1.0 is reached.

The Plugin API currently supports version 3.y of Pulp Core.

See :doc:`Plugin API <../index>` and
:doc:`Plugin Development <../plugin-writer/index>`.

0.1.0b14
========

* `List of plugin API related changes in beta 14 <https://github.com/pulp/pulp/pulls?utf8=%E2%9C%93&q=label%3A3.0+label%3Aplugin-writer+is%3Aclosed+merged%3A2018-11-21T13%3A00%3A00-04%3A00..2018-11-29T14%3A10%3A00-06%3A00+>`_


0.1.0b13
========

* `List of plugin API related changes in beta 13 <https://github.com/pulp/pulp/pulls?utf8=%E2%9C%93&q=label%3A3.0+label%3Aplugin-writer+is%3Aclosed+merged%3A2018-11-15T16%3A30%3A00-06%3A00..2018-11-21T13%3A00%3A00-04%3A00+>`_


0.1.0b12
========

* `List of plugin API related changes in beta 12 <https://github.com/pulp/pulp/pulls?utf8=%E2%9C%93&q=label%3A3.0+label%3Aplugin-writer+is%3Aclosed+merged%3A2018-10-11T15%3A00%3A00-04%3A00..2018-11-15T16%3A30%3A00-06%3A00+>`_

0.1.0b11
========

* `List of plugin API related changes in beta 11 <https://github.com/pulp/pulp/pulls?utf8=%E2%9C%93&q=label%3A3.0+label%3Aplugin-writer+is%3Aclosed+merged%3A2018-10-05T13%3A30%3A00-06%3A00..2018-10-11T15%3A00%3A00-04%3A00+>`_

0.1.0b10
========

* `List of plugin API related changes in beta 10 <https://github.com/pulp/pulp/pulls?utf8=%E2%9C%93&q=label%3A3.0+label%3Aplugin-writer+is%3Aclosed+merged%3A2018-10-01T01%3A30%3A00-06%3A00..2018-10-05T13%3A30%3A00-06%3A00+>`_

0.1.0b9
=======

* `Expose NamedModelViewSet to plugins <https://github.com/pulp/pulp/pull/3681>`_

0.1.0b8
=======

* `Problem: Distribution is not available as an abstract model <https://github.com/pulp/pulp/pull/3675>`_

0.1.0b7
=======

* `Add ContentGuard model, serializer and viewset <https://github.com/pulp/pulp/pull/3666>`_
* `Allow simpler pipeline customization in DeclarativeVersion <https://github.com/pulp/pulp/pull/3664>`_
* `Artifact is compatible with bulk_create() <https://github.com/pulp/pulp/pull/3660>`_
* `Add async batches iterator <https://github.com/pulp/pulp/pull/3643>`_

0.1.0b6
=======

* `Multi-Artifact Content units work now <https://github.com/pulp/pulp/pull/3628>`_

0.1.0b5
=======

* `Addition of the Stages API <https://github.com/pulp/pulp/pull/3559>`_
* `Removal of GroupDownloader <https://github.com/pulp/pulp/pull/3606>`_

0.1.0b4
=======

* `Use querysets for add/remove_content methods <https://github.com/pulp/pulp/pull/3548>`_

0.1.0b3
=======

* Relax dependency pinning to pulpcore

0.1.0b2
=======

* Tasking system switching from Celery+RabbitMQ to RQ+Redis. This breaking change impacts both
  plugin writers and users. See
  `the blog post about this change and how to update <https://pulpproject.org/2018/05/08/pulp3-moving-to-rq/>`_.


0.1.0b1
=======

Initial beta release
