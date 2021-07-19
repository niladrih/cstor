v2.11.0 / 2021-07-14
========================


v2.11.0-RC2 / 2021-07-12
========================


v2.11.0-RC1 / 2021-07-07
========================


v2.10.0 / 2021-06-14
========================


v2.10.0-RC2 / 2021-06-11
========================


v2.10.0-RC1 / 2021-06-08
========================


v2.9.0 / 2021-05-13
========================


v2.9.0-RC2 / 2021-05-10
========================


v2.9.0-RC1 / 2021-05-06
========================


v2.8.0 / 2021-04-14
========================


v2.8.0-RC2 / 2021-04-12
========================


v2.8.0-RC1 / 2021-04-07
========================


v2.7.0 / 2021-03-11
========================


v2.7.0-RC2 / 2021-03-10
========================


v2.7.0-RC1 / 2021-03-08
========================


v2.6.0 / 2021-02-13
========================


v2.6.0-RC2 / 2021-02-11
========================


v2.6.0-RC1 / 2021-02-08
========================


v2.5.0 / 2021-01-12
========================


v2.5.0-RC2 / 2021-01-11
========================


v2.5.0-RC1 / 2021-01-08
========================


v2.4.1 / 2020-12-18
========================


v2.4.0 / 2020-12-13
========================


v2.4.0-RC2 / 2020-12-12
========================


v2.4.0-RC1 / 2020-12-10
========================


v2.3.0 / 2020-11-14
========================


v2.3.0-RC2 / 2020-11-13
========================


v2.3.0-RC1 / 2020-11-12
========================


v2.2.0 / 2020-10-13
========================


v2.1.0 / 2020-09-14
========================
* chore(build): remove build process from repo ([#319](https://github.com/openebs/cstor/pull/319),[@mittachaitu](https://github.com/mittachaitu))


v2.0.0 / 2020-08-14
========================


v1.12.0 / 2020-07-13
========================


v1.11.0 / 2020-06-12
========================
* Fixing ubuntu version in ARM cstor-base image, issue([#3037](https://github.com/openebs/openebs/issues/3037)) ([#310](https://github.com/openebs/cstor/pull/310),[@mynktl](https://github.com/mynktl))
* Fix wrong value of CPU_SEQID causing a crash on arm64 ([#309](https://github.com/openebs/cstor/pull/309),[@sgielen](https://github.com/sgielen))


v1.11.0-RC2 / 2020-06-11
========================


v1.11.0-RC1 / 2020-06-09
========================
* Fix wrong value of CPU_SEQID causing a crash on arm64 ([#309](https://github.com/openebs/cstor/pull/309),[@sgielen](https://github.com/sgielen))
* Fixing ubuntu version in ARM cstor-base image, issue([#3037](https://github.com/openebs/openebs/issues/3037))([#310](https://github.com/openebs/cstor/pull/310),[@mynktl](https://github.com/mynktl))


1.10.0 / 2020-05-14
========================


1.9.0 / 2020-04-14
========================
* added new command listsnap under zfs to list the snapshots for dataset from cache ([#295](https://github.com/openebs/cstor/pull/295),[@vishnuitta](https://github.com/vishnuitta))
* support for ARM build, ARM images are pushed under openebs/cstor-pool-arm64 ([#296](https://github.com/openebs/cstor/pull/296),[@kmova](https://github.com/kmova))


1.9.0-RC1 / 2020-04-08
========================
* added new command listsnap under zfs to list the snapshots for dataset from cache ([#295](https://github.com/openebs/cstor/pull/295),[@vishnuitta](https://github.com/vishnuitta))
* support for ARM build, ARM images are pushed under openebs/cstor-pool-arm64 ([#296](https://github.com/openebs/cstor/pull/296),[@kmova](https://github.com/kmova))


1.8.0 / 2020-03-13
========================
* test cases for uzfs pool readonly support ([#289](https://github.com/openebs/cstor/pull/289),[@mynktl](https://github.com/mynktl))
* test cases to fetch specific snapshot information using target ([#292](https://github.com/openebs/cstor/pull/292),[@mynktl](https://github.com/mynktl))


1.8.0-RC1 / 2020-03-06
========================
* test cases for uzfs pool readonly support ([#289](https://github.com/openebs/cstor/pull/289),[@mynktl](https://github.com/mynktl))
* test cases to fetch specific snapshot information using target ([#292](https://github.com/openebs/cstor/pull/292),[@mynktl](https://github.com/mynktl))


1.7.0-RC1 / 2020-02-07
========================
* updated travis file to create /var/tmp/sock after installing dependencies ([#290](https://github.com/openebs/cstor/pull/290),[@mittachaitu](https://github.com/mittachaitu))
* added test cases for uzfs zvol readonly support ([#288](https://github.com/openebs/cstor/pull/288),[@mynktl](https://github.com/mynktl))
* updated docker script for cstor-pool to dump core on persistent location `/var/openebs/cstor-pool/core` ([#286](https://github.com/openebs/cstor/pull/286),[@mittachaitu](https://github.com/mittachaitu))
