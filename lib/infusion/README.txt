This custom build of Infusion was built from an unreleased version of Infusion's master branch (d0f009b391d89a37fd2b4698a4bc7389b5473e6f) using the following command:

ant -lib lib/rhino customBuild -Dinclude="fss" -DnoMinify="true"


Additional Modifications:
=========================

Removed all unneeded files, and kept only the following
- fss-base-global.css
- fss-reset-global.css
- fss-layout.css
- fss-text.css