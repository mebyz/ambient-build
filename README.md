# ambient-build
Ambient is a cutting edge game engine using rust, wasm, and webgpu. you can use this github action to automatically build your ambient projects upon push or PRs

## usage
consider the following part of a sample action (.yml) file located in your repo in .github/workflows/ :

''' 
...
steps:
  - uses: actions/checkout@v3
  - uses: mebyz/ambient-0.1.1-build-action@v1
...
'''

this will build your ambient project using ambient version 0.1.1
