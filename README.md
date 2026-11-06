# ui-layout-manager-v2
A layout manager for react applications.

Using my experience building the first version of [ui-layout-manager][layout-manager], I decided to start a new implementation of this library so that I can address all the issues I had while building and using that library. I will establish schemas for LDF files so that it is validated before it is imported into the layout manager. I also want to make some more long term architectural decisions about the library from the start and plan around it. For example, do I intend to use DND-kit for drag and drop across all my applications including the components in the workbench? If so, what are the nuances of how I should structure that? Or do I want to write my own? Is it worth implementing my own component library for buttons, text etc, or since this is an open source solution, does it make more sense to leverage a solution that the community is already building on? I can build the actual library functionality without worrying about the UI yet but its worth thinking about functionality like drag and drop.

I will spend some time planning this repo before I start implementation, I understand what it needs to do, I just want to build it in a maintainable way so that people can contribute to it and use it.

[layout-manager]https://github.com/vishalpalaniappan/ui-layout-manager
