---
layout: default
title: mesheryctl-model
permalink: reference/mesheryctl/model
redirect_from: reference/mesheryctl/model/
type: reference
display-title: "false"
language: en
command: model
subcommand: nil
---

# mesheryctl model

Manage models

## Synopsis

Export, generate, import, list, search and view model(s) and detailed informations
Documentation for models can be found at https://docs.meshery.io/reference/mesheryctl/model
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model [flags]

</div>
</pre> 

## Examples

Display number of available models in Meshery
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model --count

</div>
</pre> 

Export registred models
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model export [model-name]

</div>
</pre> 

Generate model(s)
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model export [model-name]

</div>
</pre> 

Import model(s)
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model import -f [Uri]

</div>
</pre> 

List available model(s)
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model list

</div>
</pre> 

Search for a specific model
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model search [model-name]

</div>
</pre> 

View a specific model
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model view [model-name]

</div>
</pre> 

Scaffold a folder structure for model creation
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model init [model-name]

</div>
</pre> 

Create an OCI-compliant package from the model files
<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model build [model-name]

</div>
</pre> 

<pre class='codeblock-pre'>
<div class='codeblock'>
mesheryctl model build [model-name]/[model-version]

</div>
</pre> 

## Options

<pre class='codeblock-pre'>
<div class='codeblock'>
      --count   (optional) Get the number of models in total
  -h, --help    help for model

</div>
</pre>

## Options inherited from parent commands

<pre class='codeblock-pre'>
<div class='codeblock'>
      --config string   path to config file (default "/home/runner/.meshery/config.yaml")
  -v, --verbose         verbose output

</div>
</pre>

## See Also

* [mesheryctl model build](/reference/mesheryctl/model/build)
* [mesheryctl model export](/reference/mesheryctl/model/export)
* [mesheryctl model generate](/reference/mesheryctl/model/generate)
* [mesheryctl model import](/reference/mesheryctl/model/import)
* [mesheryctl model init](/reference/mesheryctl/model/init)
* [mesheryctl model list](/reference/mesheryctl/model/list)
* [mesheryctl model search](/reference/mesheryctl/model/search)
* [mesheryctl model view](/reference/mesheryctl/model/view)

Go back to [command reference index](/reference/mesheryctl/), if you want to add content manually to the CLI documentation, please refer to the [instruction](/project/contributing/contributing-cli#preserving-manually-added-documentation) for guidance.
