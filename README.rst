Large examples of real Firehose data
====================================

This project contains static analysis emitted by mock-with-analysis
in Firehose format.

The directory structure is of the form:

   NAME/VERSION/RELEASE/ARCH/ANALYSIS#/sources
                                      /reports

e.g. "policycoreutils/2.1.13/27.2.fc17/x86_64/001"

The precise formats vary somewhat, as mock-with-analysis and firehose were
developed:

* policycoreutils/2.1.13/27.2.fc17/x86_64/001
  (the failures weren't captured)

* python-ethtool/0.7/4.fc19/x86_64/002
  (the failures weren't captured)

* python-ethtool/0.8/0.dc309d6b2781dc3810021d2e4e2d669f40227b63.fc17/x86_64/001
  (the failures weren't captured)

* python-ethtool/0.7/4.fc19/x86_64/003
  (added failure-capturing)

* python-ethtool/0.8/0.dc309d6b2781dc3810021d2e4e2d669f40227b63.fc17/x86_64/002
  (added failure-capturing)


The captured source code files are under their own licenses, which are
quoted here:

* policycoreutils-2.13: GPLv2 (see licenses/policycoreutils/2.13/COPYING)
* python-ethtool: GPLv2 (see licenses/python-ethtool/{0.7|0.8}/COPYING)
