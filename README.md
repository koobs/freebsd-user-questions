# FreeBSD Community and User Questions

## General Questions

### Community

### Processes

- workflow for patching/maintaining leaves some details out such as what automated steps take place, and what manual steps are present
- how to accept a patch, or as a non-committer maintainer, to indicate it's ready for the next stage? refer to maintainer flags, keywords, patch attributes
- who can mark a patch attachment as obsolete?
- what is the BZ keywords field for?

### Contributing

- please recommend some reasonably complex ports that are considered best practice; we all copy-pasta but it helps to have good sauce to refer to.
- a default / simple poudriere set up makes a huge difference to this

## Port Maintenance

Need a one-stop checklist for what to do before submitting a port
- portlint
- poudriere output
- confirming `sudo make deinstall clean fetch makesum stage stage-qa check-orphans check-plist package install` works fine
- what variants of FreeBSD should be checked (9,10,current ?) amd64? poudriere does make this easy

## Issue Tracking

### Workflow

### Triage
