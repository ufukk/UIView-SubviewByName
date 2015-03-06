# UIView-SubviewByName

Simple UIView extension that provides naming and grouping options for subviews.

Linking a subview with a name:

  [parentView addSubview:subview withName:@"sub_view"]

Or

  [parentView setNames:@[@"sub_view"] groupNames:nil forSubviews:@[subview]]

Accessing named subviews:

  [parentView subviewWithName:@"sub_view"]

Accessing multiple subviews with a name:

  [parentView subviewsWthGroupName:@"group_Name"];

Removing a named subview:

  [parentView removeSubviewWithName:@"sub_view"];

Remove multiple subviews:

  [parentView removeSubviewsWithGroupName:@"group_Name"];

