/* -------------------------------------------------------------------------
 * PACK
 *
 * The pack object simply causes any number of elements pack up horizontally to
 * automatically fill an equal, fluid width of their parent.
 *
 * Params:
 * SPACE .............................. Horizontal separation between image and body
 * ALIGNMENT .......................... Vertical items alignment

// Object variables
// --------------------------------------------------

// Object toggling

$o-pack--enabled: true !default

// Object Params

$o-pack__space: $g-reset__spacing--horizontal !default

// Modifiers Spaces

$o-pack__mod-spaces--enabled: true !default
$o-pack-spaces: map_remove($f-spaces, "large", "huge") !default

// Modifiers Alignments

$o-pack__mod-alignments--enabled: true !default
$o-pack__mod-alignments: top, middle, bottom !default

// Modifier Reverse

$o-pack__mod-reverse--enabled: true !default

// Modifier Auto Width

$o-pack__mod-auto--enabled: true !default

// Object as a mixin
// --------------------------------------------------

=o-pack($_space-value: $o-pack__space)
  width: 100%
  margin-left: 0
  display: table
  table-layout: fixed
  border-collapse: separate
  border-spacing: s-core-px-to-rem($_space-value)

=o-pack__item
  display: table-cell
  vertical-align: top

// Object selector output
// --------------------------------------------------

@if $o-pack--enabled
  .o-pack
    +o-pack

  .o-pack__item
    +o-pack__item

// Space modifiers
// --------------------------------------------------

=o-pack--space($_space-name: "none", $_space-value: 0)
  .o-pack--space-#{$_space-name}
    border-spacing: s-core-px-to-rem($_space-value)

@if $o-pack--enabled and $o-pack__mod-spaces--enabled
  @each $_space-name, $_space-value in $o-pack-spaces
    +o-pack--space($_space-name, $_space-value)

// Alignment modifiers
// --------------------------------------------------

=o-pack__mod-alignment($_vertical-alignment: top)
  .o-pack--#{$_vertical-alignment} > .o-pack__item
    vertical-align: $_vertical-alignment

@if $o-pack--enabled and $o-pack__mod-alignments--enabled
  @each $_vertical-alignment in $o-pack__mod-alignments
    +o-pack__mod-alignment($_vertical-alignment)

// Reverse modifier
// --------------------------------------------------

=o-pack--reverse
  direction: rtl

=o-pack__item--reverse
  direction: ltr

@if $o-pack--enabled and $o-pack__mod-reverse--enabled
  .o-pack--reverse
    +o-pack--reverse

    > .o-pack__item
      +o-pack__item--reverse

// Auto-Width modifier
// --------------------------------------------------

=o-pack--auto
  table-layout: auto

@if $o-pack--enabled and $o-pack__mod-auto--enabled
  .o-pack--auto
    +o-pack--auto

// Unset as a mixin
// --------------------------------------------------

=o-pack--unset
  width: auto
  margin-left: inherit
  display: inherit
  table-layout: inherit
  border-collapse: inherit
  border-spacing: inherit

=o-pack__item--unset
  display: inherit
  vertical-align: inherit
