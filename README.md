# ImageBuilder
An example cloudformation template for a Generic EC2 Image Builder pipeline to demonstrate the ease of creating hardened images.

A simple image builder pipeline, recipe and distribution config which creates a STIG hardened windows 2016 image that is tested with AWS inspector for CIS findings.

Once this cloudformation is run it will automatically trigger a build of the hardened image (check ec2 for build and test instance give it a few mins)