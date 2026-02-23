# CDK-Samples

## Overview

- My working repository of `AWS-CDK` samples, walkthroughs and notes to improve/refine my understanding
- [CDK github](https://github.com/aws/aws-cdk)

## Prerequisites/Initial Setup

- [Prerequisites](https://docs.aws.amazon.com/cdk/v2/guide/prerequisites.html)
- Updated [node](https://nodejs.org/en) to version `24.13.1` on `Sunday, 22-February-2026`
- See [AWS CLI change-log](https://raw.githubusercontent.com/aws/aws-cli/v2/CHANGELOG.rst)
- Install via: `https://awscli.amazonaws.com/AWSCLIV2-2.33.27.msi`
- Installed version `2.33.27` on `Sunday, 22-February-2026`
- Install [CDK](https://docs.aws.amazon.com/cdk/v2/guide/getting-started.html): `npm install -g aws-cdk`
- Configure `aws` command-line: `export AWS_PROFILE=app-deployer-dev`
- Check connection: `aws sts get-caller-identity`

## `Sunday, 22-February-2026`

- Working through [this](https://docs.aws.amazon.com/solutions/latest/constructs/walkthrough-part-1-v2.html)
- Worked great!
- Now trying [follow-up](https://docs.aws.amazon.com/solutions/latest/constructs/walkthrough-part-2-v2.html)
- Destroy resources: `cdk destroy [stack-name] --force`
- Ultimately, couldn't get this sample to work due to version mismatches between the `V2` and `V3` api's and javascript and whatever
- Very interesting though, punting for now...
