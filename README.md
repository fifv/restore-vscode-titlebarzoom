## Motivation

From v1.72, vscode's titlebar zoom can't be less than 0

This script is used to hack vscode's code to force enable titlebar zoom. It also fix checksum.

## Usage

1. modify `vscodeRootPath` in `restore-vscode-titlebarzoom.ts` to your vscode's install dir
2. execute `restore-vscode-titlebarzoom.ts`, I recommend using `tsx` tool to execute it.

* This script just do search and replace, so you can do it yourself In your favorite language.

## Credit

Fix checksum logic is copied from
[Fix VSCode Checksums](https://marketplace.visualstudio.com/items?itemName=lehni.vscode-fix-checksums)
