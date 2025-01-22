## Scaler ecommerce microservices

## Setup
- run `git clone --recurse-submodules <repo-url>` to clone with all the submodules
- if already cloned without submodule run `git submodule update --init --recursive`

#### Steps to add MS
- create a module inside the parent using intellij or copy the start.spring.io folder here
- go to the module and run `git init`
- push the repo to relevant origin
- goto parent
- run `git submodule add <repository-url> <path>`
- run `git submodule update --init --recursive`
- commit the changes
- push to the repo