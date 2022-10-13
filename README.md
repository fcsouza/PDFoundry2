# PDFoundry2

PDFoundry2 its just a fork of PDFoundry working with Foundry V10 Update, all credits goes to [Andrew Cuccinello.](https://github.com/lozalojo)

If you have a suggestion you are welcome to open a pull request and collaborate.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/fcsouza/PDFoundry2)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/fcsouza/PDFoundry2/Release%20Module)
[![GitHub issues](https://img.shields.io/github/issues/fcsouza/PDFoundry2)](https://github.com/fcsouza/PDFoundry2/issues)
[![GitHub license](https://img.shields.io/github/license/fcsouza/PDFoundry2)](https://github.com/fcsouza/PDFoundry2/blob/master/LICENSE)
[![GitHub pull requests](https://img.shields.io/badge/pull%20requests-welcome-green)](https://github.com/fcsouza/PDFoundry2/compare)

![GitHub All Releases](https://img.shields.io/github/downloads/fcsouza/PDFoundry2/total)
![GitHub Releases](https://img.shields.io/github/downloads/fcsouza/PDFoundry2/latest/total)

PDFoundry2 (pronounced *Pee-Dee-Foundry2*/*pi di ˈfaʊndri*) is a *fully featured* PDF viewer for FoundryVTT!  PDFoundry2 supports a full suite of features for viewing PDFs right in Foundry VTT. Fillable forms, bookmarks, page links in journals and LOTS more. You can even use a form fillable PDF character sheet for an actor!

#### Thanks to
Spanish localization: [José E. Lozano (lozalojo)](https://github.com/lozalojo)

French localization: [Baktov](https://github.com/Baktov)

## Community Resources
[Tutorials and resources created by users of PDFoundry can be found here](https://github.com/Djphoenix719/PDFoundry/wiki/Community-Resources)

## Setup
PDFoundry2 is easily installable - find it in the modules list inside Foundry VTT. Alternatively, you can use the manifest link below.

### Manifest
> https://raw.githubusercontent.com/fcsouza/PDFoundry2/master/module.json

## System Developers
I highly recommend you do not bundle PDFoundry - if you do however, the module version will disable itself and display a warning to the user. Instead, you can see the [documentation](https://fcsouza.github.io/PDFoundry2/index.html) for an example of checking for the presence of PDFoundry2, and enabling additional support if it is found.

### Building PDFoundry2
If you wish to build PDFoundry2 yourself - most commonly because you want to contribute - you can do the following.

1. Clone the repository anywhere
2. Copy `foundryconfig.example.json` and rename it `foundryconfig.json`. Edit the dataPath to your data folder.
2. Open a terminal, navigate to the repository directory
3. Run `npm install`
4. Run `gulp build` to perform a one off build, or `gulp watch` to perform incremental builds as you change things

### API Examples

See the [documentation](https://fcsouza.github.io/PDFoundry2/index.html) for details and examples.
