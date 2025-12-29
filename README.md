<!-- START BLUEPRINT-MANAGED README -->

> [!IMPORTANT]
> This project is an unofficial project hosted on the [`blueprint-community`](https://github.com/blueprint-community) GitHub organization.
> [Blueprint](https://blueprint.zip) does not create, endorse or maintain these projects.
>
> You are free to contribute, fork and reuse sections of this codebase [in accordance with this projects' license](LICENSE).

<br>

<h2 align="center"> Blueprint Export Action </h2>
<p align="center"> This GitHub Action can be used to export the source code of a blueprint addon to a .blueprint file </p>

<br>

<!-- END BLUEPRINT-MANAGED README -->

## How to Use
The action has one output, FILE. This can be used in a workflow with the following variable: `${{ steps.blueprint_build.outputs.FILE }}`

An example of this in use can be found [here](https://github.com/zephrynis/ptero-sidebar/blob/main/.github/workflows/export_ext.yml).
