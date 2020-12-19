# Vim-applescript
Syntax file from: http://www.fastnlight.com/syntax/applescript  
  
## Usage
### Commands (for Mac)
`:[range]AppleScriptRun`  
Execute current buffer as AppleScript.  
   
`:[range]AppleScriptExport`  
Export current buffer as AppleScript.  
  
## Config
`g:applescript_config.run.output.buffer_name`  
The output buffer's name used in `:AppleScriptRun` commmand.  
Default: `'[AppleScriptRun Output]'`  
  
`g:applescript_config.run.output.open_command`  
A command to open output buffer used in `:AppleScriptRun` command.  
Default: `'botright split'`  
  
`g:applescript_config.indent.continuation_multiplier`  
Indentation multiplier of line which next to continuation character `¬` appears.  
Default: `2`

