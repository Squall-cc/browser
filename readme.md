# aspen browser app
pulsar browser using webrtc.

## todo:

1. forward/back button + history
2. make icon
3. make script to do pulsar build steps
4. shove eruda devtools in
5. downloads integration with fs api


## building
use 'bun run --bun vite build'

how 2 get pulsar to build:
1. clone pulsar in same folder
2. in package.json, add "workspaces": ["packages/*"],
3. build should work, files in dist folder