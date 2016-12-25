# Alpine Node with Yarn

Installing yarn the recommended way *(not via npm install)*

## Example Size Differences
| Image | Size | Notes |
| --- | --- | --- |
| mhart/alpine-node:base-6.9.2 | 38.2 MB | Base Image |
| desaias/alpine-node-yarn | 52.4 MB | Node with Yarn (recommended install) *This Dockerfile* |

| Image  | Size | Notes  |
| ---  | ---  | ---  |
| node:6.9.2-alpine  |50.7 MB  | Base Image  |
| node:6.9.2-alpine w/yarn | 65 MB  | Recommended way of installing yarn |
| node:6.9.2-alpine w/yarn via npm | 79.3 MB | Built with installing yarn via npm install -g yarn |


