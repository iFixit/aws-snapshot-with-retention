Create snapshots of Amazon EBS volumes and clean up snapshots once they're old.

There are many, many scripts to do things like this.  It seems, however, that
half of them require large SDKs, and the other half don't work.  This is an
attempt to make a tool that has very simple dependencies and works
consistently.

It lacks sophistication, but that is on the roadmap.

# Installation

`snapshot-with-retention` has one direct dependency, [aws-cli].  Please refer
to [their installation instructions][aws-cli-install]; for most people, it's
one command.

[aws-cli]: https://github.com/aws/aws-cli
[aws-cli-install]: https://github.com/aws/aws-cli#installation

Then, simply put `snapshot-with-retention` somewhere and call it.

