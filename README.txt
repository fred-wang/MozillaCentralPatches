This my set of patches for mozilla-central. They are of various kinds: patches
that I'm currently working on, patches written by others that I need to apply
before my own patches, experimental patches, old patches etc Of course, most of
them are related to MathML ;-)

Because most of the patches are unmaintained or work in progress, I can not
guarantee the stability of this set of patches. Conflicts may appear between
patches or with mozilla-central changes. However, I give below a list of the
patches that I think stable enough for other people to use them. They are
patches that are going to land or that I think ready for the review process.

My actual patch queue is described by the usual Mercurial files "series" and
"status". The former gives the order in which patches are supposed to be
applied. The latter indicates those that are currently applied. In particular,
note that I'm only applying and compiling the patches in "status" before
pushing to GitHub. However, please tell me if you find any issue with the
stable patches below and I'll try to update them as soon as possible.

* Stable patches

  { assertion-716349.diff
  { crashtest-716349.diff

  { download-fonts-1.diff
  { download-fonts-2.diff

  { remove-stix-beta.diff

* Work in progress patches:

  { remove-namedspace-atoms.diff
    => See bug 673759 comment 16.

  { mglyph-1.diff
  { mglyph-2.diff
  { mglyph-3.diff
    => May crash Mozilla.

  { ms-quotes-1.diff
  { ms-quotes-2.diff
  { ms-quotes-3.diff
    => Need feedback for the style part, fail dir=rtl and setAttribute tests.

* Experimental and old patches:

  - try.diff (used to push to try server)
  - largeop-initial-stretch.diff
  - opdict-diagonal-arrows.diff
  - rotate_stretchy.diff
  - mo-selection.diff
  - math-height.diff
  - mathml_localize.diff
  - mathml_linebreak.diff
