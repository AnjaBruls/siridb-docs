---
title: "create group"
weight: 49
---

Syntax:

	create group `groupname` for /regular_expression/

Groups should be between **backticks** to make them different from strings.
Since a group is basically a cached regular expression we need to provide
the regular expression we want to use for the group.

If you want to drop an existing group see [drop groups](../drop_groups).

Example:

	# Create a group linux
	create group `linux` for /linux.*/
