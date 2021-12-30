January brings us Firefox 85

To wrap up January, we are proud to bring you the release of Firefox 85. In this version we are bringing you
support for the :focus-visible pseudo-class in CSS and associated devtools, and the complete removal of Flash
support from Firefox

################################

he release of Apple Silicon-based Macs at the end of last year generated a flurry of news coverage and some surprises at the machine’s performance. This post details some background information on the experience of porting Firefox to run natively on these CPUs.
We’ll start with some background on the Mac transition and give an overview of Firefox internals that needed to know about the new architecture, before moving on to the concept of Universal Binaries.
We’ll then explain how DRM/EME works on the new platform, talk about our experience with macOS Big Sur, and discuss various updater problems we had to deal with. We’ll conclude with the release and an overview of various other improvements that are in the pipeline.