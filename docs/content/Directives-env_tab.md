---
title: "Directives: start_of_tab"
description: "Directives: start_of_tab"
---

# Directives: start_of_tab

Abbreviation: `sob`.

This directive indicates that the lines that follow form a section of
guitar TAB instructions. The lines will not be folded or changed.
Markup is left as is, and directives are considered literal
text except for `{end_of_tab}` and `{eot}`.

This directive may include an optional label, to be printed in the
left margin. For example:,

    {start_of_tab: Solo}

The ChordPro reference implementation prints the label in the left
margin, see [labels]({{< relref "ChordPro-Configuration-PDF#labels" >}}).

# Directives: end_of_tab

Abbreviation: `eot`.

This directive indicates the end of the tab.
