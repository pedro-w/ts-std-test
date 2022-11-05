# Test Code

This is a minimal test-repository to cause a crash in the VSCode extension
for ts-standard. 
Note that it doesn't compile or do anything useful.

1. Start with a working installation of `vscode-standard` loaded into VSCode
2. Clone this repo somewhere and `npm i`
3. In VSCode, start the extension (using launch profile 'Client + Server')
4. Open the folder containing this repo
5. Open the file `src/index.ts`
6. The modeline at the bottom of the screen will osciallate a few times
   between 'Typescript' and 'Typescript standard style' then the error
   message will appear.