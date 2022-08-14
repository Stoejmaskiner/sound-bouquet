# Sound Bouquet
Audio sample manager, metadata manager and batch editor for quick editing of large sample packs. Written in C# with the .NET framework. 

## Roadmap

This is a solo project. It will take a long time to develop and will help me deepen my knowledge of .NET developemnt and audio programming along the way. Currently work is being done on the specification and prototyping aspects of things. As a stepping stone to developing this application, other middleware needs to be developed, to interface with the file formats that I want to support (first priority is given to WAV, AIFF and FLAC; second priority to MP3 and OGG Vorbis)

A rough outline of the milestones are as follows, they will be iterated through multiple times.

First iteration: development of a minimum viable product (MVP) prototype
- [ ] initial MVP requirement specification
- [ ] requirement specification of a minimal set of reusable sub-modules (for handling file I/O for example)
- [ ] initial design of these sub-modules
- [ ] prototyping of these sub-modules
- [ ] design of MVP using sub-module prototypes
- [ ] development of MVP
- [ ] testing and documentation of MVP

Second iteration: using the insight gained in the development of an MVP, a more robust and large scale architecture and maintenance plan needs to be formulated, and the full-scale application is developed, some code reuse may happen, but this is largely expected to be a complete re-write.
- [ ] TBA

## Pitch

Imagine you make sample packs, either commercially or in order to manage your own sample library. The audio editors you can choose from are great on single samples, but are clunky and impractical for working on batches of samples. On the other hand, sample managers are great at renaming, tagging and moving batches of samples, but have few or no editing tools. Sound Bouquet comes to the rescue, offering batch editing and management tools that allow you to quickly apply common edits to the audio and metadata across a selection of files. You can apply normalization, you can chop samples so that they match in length or so that they don't exceed a certain length, you can fade samples in and out, you can splice a sample into multiple samples, which are saved and named automatically, you can use patterns that automatically generate file names for a selection of samples, you can convert a batch of files of different formats into a common format, you can automatically trim silence from the start of samples.
