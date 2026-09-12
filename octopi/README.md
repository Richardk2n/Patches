# Reasoning

At the moment displaying the diff using octopi displays the last diff.  
This can hide updates if they happen in quick succession.  
`diffSinceInstall.patch` changes this to display the diff since the install date of the package.  
This is already merged but not yet published.  
Note, that this is based on the Manjaro PKGBUILD which has differences to the AUR one in regard to the notifier.
