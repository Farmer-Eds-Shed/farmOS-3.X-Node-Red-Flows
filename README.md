# farmOS-3.X-Node-Red-Flows

## Overview
This repository contains Node-RED flows for integration with farmOS 3.X. These flows are designed to help manage and automate various aspects of farm operations.

## Getting Started
To get started with these Node-RED flows, follow the steps below:

- **Clone Repo**
   ```sh
   git clone https://github.com/Farmer-Eds-Shed/farmOS-3.X-Node-Red-Flows.git
   cd farmOS-3.X-Node-Red-Flows
- **Open Node-Red**
   - [ctrl-]-i
   - Import file

- **Choose file**
   1. **Oauth2-example-flow.json** farmOS Authentication flow.
   1. **Taxonomy-initialization-flow.json** Subrequests example to import herd code taxonomy from a CSV file with 2 headings **Breed** and **Code**.
   1. **Herd-initialization-flow.json** Flow to initialize a new livestock farmOS instance - Pulls data from another API that is already saved to flow context (Details of other API not included).
   
