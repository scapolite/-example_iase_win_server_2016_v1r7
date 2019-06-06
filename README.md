# Scapolite Example: IASE Windows Server 2016 STIG V1R7

## Background

From April 30th to May 2nd 2019, NIST conducted a workshop on the
future of [SCAP](https://csrc.nist.gov/Projects/Security-Content-Automation-Protocol-v2).

During the workshops, the participants in the break-out sessions on the
future of XCCDF decided on founding a [work
group](https://groups.google.com/a/list.nist.gov/forum/#!forum/scap-dev-authoring)
on improving authoring and maintenance of SCAP content as manageable
text files under version control such as practiced by Red Hat's
[Compliance-as-Code project](https://github.com/ComplianceAsCode/content) and Siemens'
[Scapolite
format](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/grobauer_siemens_scap_v2_experiences_scapolite.pdf)

The participants agreed that Siemens' Scapolite format looked like a promising candidate to be used as basis for a standard format and that it should be further evaluated. As first step in this evaluation, a complete example of
SCAP content maintained in Scapolite rather than XCCDF+OVAL should be published.

This repository contains such an example.

## Contents of this repository

This content has been produced from an import of the *IASE Windows Server 2016 STIG V1R7*
SCAP datastream into the Scapolite format:

- Folder `scapolite` contains the Scapolite representation of the STIG:

  - the design of Scapolite allows the maintenance of each rule
    as a single file rather than maintaining the complete
    baseline within one huge XML file
  - the combination of a YAML preamble and a Markdown body
    allows authors to leverage the preview capabilities of
    modern editors, e.g., [Visual Studio Code](https://code.visualstudio.com) or [Atom](https://atom.io), and web sites such as [GitHub](https://github.com) or [GitLab](https://gitlab.com/).
  - rules can be augmented with machine-readable information
    either within the rule file (e.g., the machine-readable
    information on Windows GPO settings and their underlying
    implementation mechanisms) as well as outside the file
    (as practiced in this example with the OVAL checks; those
    could be included also within the rule file, but the
    very verbose XML syntax of OVAL makes this a bit cumbersome).

- Folder `sources` contains the source XML which was imported

- The following files are exports of the content which have been carried
  out with proof-of-concept tooling for working with `Scapolite`:

  - `iase_win_server_2016_v1r7_scapolite_export.xlsx`

    An Excel-representation of all rules of the STIG
  - `iase_win_server_2016_v1r7_scapolite_export.pdf`

    A PDF representation of the STIG

  - `iase_win_server_2016_v1r7_scapolite_export-ds.xml`

    An experimental SCAP export from the Scapolite sources carried
    out by Siemens' `scaptain` tool (transforming Scapolite into
    XCCDF and OVAL) and Red Hat's excellent `oscap` tool for
    combining the resulting files into a single datastream.

    Note that this export does not include the full information within
    the Scapolite file (e.g., references have been left out); the
    intention of the file is to serve as proof of concept for
    maintaining content in Scapolite for authors and maintainers and
    exporting to SCAP for consumption by SCAP checkers.

Please refer to the [slide set about Scapolite](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/grobauer_siemens_scap_v2_experiences_scapolite.pdf)
that has been presented at NIST's SCAP v2 workshop for more information about Scapolite.

The machine-readable information on how to implement the settings
is **not** part of the original IASE DISA STIG; the information
has been added using the mechanisms described in the
[slide set about automating implementation](https://github.com/scapolite/docs/raw/master/201905_scap_v2_workshop/stoeckle_tum_scap_v2_scapolite_automated_implementation.pdf)
that has been presented at NIST's SCAP v2 workshop, too.

**ATTENTION**

Copyright holder for the contents of the IASE Windows Server 2016 STIG V1R7 is IASE DISA,
please refer to [DoD CyberExchange Website](https://public.cyber.mil/stigs/downloads/) for
information about the STIGs and access to the authoritative versions of the STIGs.

This project merely uses the STIG as an example of how SCAP content can be expressed
and enriched in Scapolite.

## Questions and Feedback

For feedback/questions/discussion please use the mailing list:

<https://list.nist.gov/scap-dev-authoring>
