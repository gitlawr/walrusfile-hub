# Walrus File Hub

A curated list of Walrus file samples.

## Getting Started

### Prerequisites

- Installed [Walrus](https://github.com/seal-io/walrus).

### Deploying a sample

The directory of each sample contains a yaml file that can be deployed with Walrus. Check the README.md of each sample to get more details on the structure of a deployment. You can deploy a sample using the following methods:

#### Using the Walrus CLI

The Walrus CLI is a command line tool that can be used to deploy a sample. Install the CLI by heading to the Walrus release page and downloading the binary for your platform. Once installed, deploy a sample using the following command:

```bash
# Log in to your Walrus server
walrus login
# Deploy a sample
walrus apply -f <sample.yaml>
```

#### Using the Walrus UI

Deploy a sample using the Walrus UI. Log in to your Walrus server and then click on the "Import YAML" button in the top right corner of the resource list page. Select the YAML file of the sample you want to deploy and click on "Import". The sample will be imported and deployed.

## Contributing

### Adding a sample

To add a sample, you need to create a new directory in the root of this repository. The name of the directory should be the name of the sample. The directory should include a README.md file that describes the sample and a yaml file that defines the resources of the sample. Optionally, you can also include an icon file that will be used as the icon of the sample in the Walrus UI. The directory should have the following structure:

```
sample-name
├── README.md
├── sample-name.yaml
└── icon.{png,svg,jpg,jpeg}
```

## License

Copyright (c) 2024 [Seal, Inc.](https://seal.io)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [LICENSE](./LICENSE) file for details.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.