# cti-documentation

*This is an [OASIS TC Open Repository](https://www.oasis-open.org/resources/open-repositories/). See the [Governance](#governance) section for more information.*

This repository is a GitHub Pages site storing non-normative information about the work of the CTI Technical Committee.

## Developing

Setting up a development environment requires a working Ruby environment (for Jekyll), and a working Python environment (for running git hooks and validating examples).

The following commands should help:

```bash
gem install bundler
bundle install

pip install pre-commit
pre-commit install
pre-commit install --hook-type pre-push

pip install stix2-validator
```

To build the documentation, run:

```
bundle exec jekyll serve --incremental
```

To test that examples are valid before pushing:

```
./validate-examples.sh
```


## Governance

This GitHub public repository ( **[https://github.com/oasis-open/cti-documentation](https://github.com/oasis-open/cti-documentation)** ) was [proposed](https://lists.oasis-open.org/archives/cti/201609/msg00001.html) and [approved](https://www.oasis-open.org/committees/ballot.php?id=2971) [[bis](https://issues.oasis-open.org/browse/TCADMIN-2435)] by the [OASIS Cyber Threat Intelligence (CTI) TC](https://www.oasis-open.org/committees/cti/) as an [OASIS TC Open Repository](https://www.oasis-open.org/resources/open-repositories/) to support development of open source resources related to Technical Committee work.

While this TC Open Repository remains associated with the sponsor TC, its development priorities, leadership, intellectual property terms, participation rules, and other matters of governance are [separate and distinct](https://github.com/oasis-open/cti-documentation/blob/master/CONTRIBUTING.md#governance-distinct-from-oasis-tc-process) from the OASIS TC Process and related policies.

All contributions made to this TC Open Repository are subject to open source license terms expressed in the [BSD-3-Clause License](https://www.oasis-open.org/sites/www.oasis-open.org/files/BSD-3-Clause.txt). That license was selected as the declared ["Applicable License"](https://www.oasis-open.org/resources/open-repositories/licenses) when the TC Open Repository was created.

As documented in ["Public Participation Invited](https://github.com/oasis-open/cti-documentation/blob/master/CONTRIBUTING.md#public-participation-invited)", contributions to this OASIS TC Open Repository are invited from all parties, whether affiliated with OASIS or not. Participants must have a GitHub account, but no fees or OASIS membership obligations are required. Participation is expected to be consistent with the [OASIS TC Open Repository Guidelines and Procedures](https://www.oasis-open.org/policies-guidelines/open-repositories), the open source [LICENSE](https://github.com/oasis-open/cti-documentation/blob/master/LICENSE) designated for this particular repository, and the requirement for an [Individual Contributor License Agreement](https://www.oasis-open.org/resources/open-repositories/cla/individual-cla) that governs intellectual property.

## <a id="maintainers">Maintainers</a>

TC Open Repository [Maintainers](https://www.oasis-open.org/resources/open-repositories/maintainers-guide) are responsible for oversight of this project's community development activities, including evaluation of GitHub [pull requests](https://github.com/oasis-open/cti-documentation/blob/master/CONTRIBUTING.md#fork-and-pull-collaboration-model) and [preserving](https://www.oasis-open.org/policies-guidelines/open-repositories#repositoryManagement) open source principles of openness and fairness. Maintainers are recognized and trusted experts who serve to implement community goals and consensus design preferences.

Initially, the associated TC members have designated one or more persons to serve as Maintainer(s); subsequently, participating community members may select additional or substitute Maintainers, per [consensus agreements](https://www.oasis-open.org/resources/open-repositories/maintainers-guide#additionalMaintainers).

**<a id="currentMaintainers">Current Maintainers of this TC Open Repository</a>**

 * [Jason Keirstead](mailto:Jason.Keirstead@ca.ibm.com); GitHub ID: [https://github.com/JasonKeirstead](https://github.com/JasonKeirstead); WWW: [IBM](http://www.ibm.com/)
 * [Emily Ratliff](mailto:Emily.Ratliff@ibm.com); GitHub ID: [https://github.com/ejratl](https://github.com/ejratl); WWW: [IBM](http://www.ibm.com/)
 * [Duncan Sparrell](mailto:duncan@sfractal.com); GitHub ID: [https://github.com/sparrell](https://github.com/sparrell); WWW: [sFractal](http://sfractal.com/)

## <a id="aboutOpenRepos">About OASIS TC Open Repositories</a>

 * [TC Open Repositories: Overview and Resources](https://www.oasis-open.org/resources/open-repositories/)
 * [Frequently Asked Questions](https://www.oasis-open.org/resources/open-repositories/faq)
 * [Open Source Licenses](https://www.oasis-open.org/resources/open-repositories/licenses)
 * [Contributor License Agreements (CLAs)](https://www.oasis-open.org/resources/open-repositories/cla)
 * [Maintainers' Guidelines and Agreement](https://www.oasis-open.org/resources/open-repositories/maintainers-guide)

## <a id="feedback">Feedback</a>

Questions or comments about this TC Open Repository's activities should be composed as GitHub issues or comments. If use of an issue/comment is not possible or appropriate, questions may be directed by email to the Maintainer(s) [listed above](#currentMaintainers). Please send general questions about TC Open Repository participation to OASIS Staff at [repository-admin@oasis-open.org](mailto:repository-admin@oasis-open.org) and any specific CLA-related questions to [repository-cla@oasis-open.org](mailto:repository-cla@oasis-open.org).
