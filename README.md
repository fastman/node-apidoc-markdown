# apidoc-markdown2

Generate API documentation in markdown from [apidoc](https://github.com/apidoc/apidoc) data.

## Installation

	npm install apidoc-markdown2

## Usage

	Usage: apidoc-markdown2 -p [path] -o [output file]

	Options:
	  --path, -p      Path to generated apidoc output. Where api_data.json & api_project.json resides.  [required]
	  --output, -o    Output file to write.                                                             [required]
	  --template, -t  Path to EJS template file, if not specified default template will be used.
	  --prepend       Prepend file after TOC.

## Examples

Generate from included example data

	apidoc-markdown2 -p examples -o examples/example.md


[View generated example](https://github.com/softdevstory/node-apidoc-markdown/blob/master/examples/example.md)

# Why apidoc-markdown2

apidoc-markdown is not maintained for long time. New tags of apidoc are not supported. This version is applied pull request for supporting new tags.