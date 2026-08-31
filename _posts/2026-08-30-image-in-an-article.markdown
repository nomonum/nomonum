---
title: "An article with an image"
category: informatics
---

This is the default: a plain paragraph reads at a normal, comfortable
width even though the page itself is wide now — the extra space is there
for laying things out, not for stretching every line of text.

An image with no classes at all sits full width of that text column,
same as before:

![A junk drawer, unsorted](/assets/images/junk.JPG)

## A photo and text, side by side

Wrap two blocks in a row and size them — no text wrap, no float, just two
clean rectangles sitting next to each other:

<div class="row" markdown="1">
![A junk drawer, unsorted](/assets/images/junk.JPG){: .col-half}

This text block sits beside the photo at half width. It doesn't wrap
around the image the way floated text used to — it's its own block,
occupying its own half of the row, with a fixed gap between the two.
{: .col-half}
</div>

## A single block, positioned right

A row can hold just one sized block and be pushed to either side:

<div class="row justify-right" markdown="1">
![A junk drawer, unsorted](/assets/images/junk.JPG){: .col-third}
</div>

## A wider block, centered

<div class="row justify-center" markdown="1">
![A junk drawer, unsorted](/assets/images/junk.JPG){: .col-two-thirds}
</div>

## A full-bleed image

![A junk drawer, unsorted](/assets/images/junk.JPG){: .img-full}

`.img-full` breaks a standalone image out edge-to-edge of the browser —
still available outside of rows, for a photo you want full weight.

## Aligning text

Regular paragraphs are left-aligned by default, like this one.

This paragraph is right-aligned.
{: .text-right }

This paragraph is centered.
{: .text-center }
