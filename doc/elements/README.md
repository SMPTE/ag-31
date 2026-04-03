# <Document or project title>

{{#if the repository is public}}
_This repository is public._
{{else}}
_This repository is private accessible only to SMPTE Standards Community members._
{{/if}}

{{#if the repository is for a PCD}}
This Committee Draft is made available for a public review period ending no
earlier than <enter date>, and no later than <enter date>.

This material is work under development and shall not be referred to as a SMPTE
Standard, Recommended Practice, or Engineering Guideline. It is distributed for
review and comment; distribution does not constitute publication.
{{/if}}

{{#if the repository is for `html-pub` tooling}}
* [Latest version](https://doc.smpte-doc.org/${repository}-private/main/)
* [Latest version (all artifacts)](https://doc.smpte-doc.org/${repository}-private/main/pub-artifacts.html)
{{/if}}

## Notices

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md) and [PATENTS.md](./PATENTS.md) for
important notices.

Unless specified otherwise, the contents of this repository are licensed as
indicated at [LICENSE.md](./LICENSE.md).

All published version(s) of this document can be found at <https://pub.smpte.org/doc/${repository}/>

## Reporting issues

Issues should be reported at <https://github.com/SMPTE/${repository}/issues>.

{{#if the repository is public}}
## Contributing
The draft version(s) of this document is accessible to SMPTE Standards Community members at <https://github.com/SMPTE/${repository}-private>.
{{/if}}
