# dsh-layout-rail

Restores the right side of the DeepSeek Harness window: the vertical **icon
rail** (Editor, Source control, Files, Trash, Terminal) that opens each right
Sidebar tab.

The rail is declared by \`ui-layout\`. A Desktop build whose \`ui-layout\` predates
that slot shows no rail, so this package replaces the \`ui-layout\` row with a build
that declares it. Install it only when the rail is missing.

## Install

In the DeepSeek Harness Desktop Plugin Manager choose **Add plugin** and enter:

\`\`\`
github:EmmanuelMartinez/dsh-layout-rail#v1.0.0
\`\`\`

Then restart the application. Plugins do not auto-update: uninstall and
reinstall to move versions.
