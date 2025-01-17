# ProgressSpinner

ProgressSpinner is a Kivy widget to display an Android Lollipop style progress spinner.

About this Fork
---------------

This package builds on a lot of good work of other people, including :
  - The original [kivy.garden.progressspinner](https://github.com/kivy-garden/garden.progressspinner), 
  written by @kived and contributed to over the years by others.  
  - Fork by [@stimpe](https://github.com/stimpe/garden.progressspinner), making the package pip installable.
  - At the time of the fork, upstream has remained unchanged 
  for 8 years. 
  - The fork has remained unchanged for 2 years. 

This is forked from `stimpe/garden.progressspinner` for the sole purpose of 
making it pip installable from PyPI. and will be made available as the 
`kivy_garden.ebs.progressspinner` package on PyPI. 

This package has no dependencies in the ebs namespace - it is simply used as 
a convenient way to differentiate from the upstream package and restrict 
namespace pollution to within the existing ebs namespace.

If you are considering using this: 

  - The original package works just fine, and has been working unmodified for 
  almost a decade at the time of this fork. No development is required or 
  planned. If you're fine with 'garden install progressspinner', don't use this
  fork.
  - If upstream makes itself pip installable, this fork and the associated PyPI 
  package will likely become unmaintained.
  - Some minor work may be needed to done to bring this in line with the new 
  `kivy_garden` format. I'm not actively working on this, but if the need for 
  it arises in form or another, I might look into it. Create an issue if you 
  have a use case which calls for it.
  
If you do end up using this package - especially if you do so in a 
production setting - please reach out to me and let me know by email at 
shashank at chintal dot in. The number of users, if any, is likely to 
determine how much effort I will put into maintaining this.


## Demo

![Example animation](progspin.gif)
