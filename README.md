# Usage

First, need to download prerequisite packages

`wget --input-file=packages/packages.list`

Empty `build` directory

Run the below command to build the final cross-compiler:

`./generate packages output build`

In which:

`packages`: directory which contains packages to build

`output`: directory which contains cross-compiler after building

`build`: temporary directory to build packages
