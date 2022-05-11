title: Intellij
author:
  name: Rubén Pulido
style: basic-style.css
output: index.html
controls: false

--
# Intellij

--
### Outline
- Installing, updating & rolling back
- Debugging
- Git
- DB
- Shortcuts
- Useful settings
- Useful plugins
- IJ (your best friend in Liferay)
--
### Installing, updating & rolling back
--
### Installing Jetbrains Toolbox
```code
brew cask install "jetbrains-toolbox"
```
--
### Installing Intellij from Jetbrains Toolbox
<img 
  src="./images/toolbox.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
-- 
### Updating & Rolling back Intellij from Jetbrains Toolbox
<img 
  src="./images/update-or-rollback.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Opening projects
<img 
  src="./images/projects.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Debugging
--
### Start Portal in Debug Mode
```
<TOMCAT_DIR>/bin/catalina.sh jpda start
```
--
### Create a remote JVM Debug Configuration
 <img 
  src="./images/remote-jvm-debug-configuration.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Connect to target VM
 <img 
  src="./images/debug.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />

 <img 
  src="./images/connected-to-target-vm.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Setting a breakpoint
 <img 
  src="./images/breakpoint.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Debugger
 <img 
  src="./images/debugger.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Stepping
 <img 
  src="./images/stepping.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
- Step over
- Step into
- Force Step into
- Step out
- Drop Frame
- Run to cursor
--
### Add to watches
 <img 
  src="./images/add-to-watches.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Watches
 <img 
  src="./images/watches.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Watches can contain expressions
 <img 
  src="./images/watches-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />

 <img 
  src="./images/watches-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Evaluate expression (1)
 <img 
  src="./images/evaluate-expression.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Evaluate expression (2)
 <img 
  src="./images/evaluate-expression-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Set value (1)
 <img 
  src="./images/set-value.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Set value (2)
 <img 
  src="./images/set-value-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Conditional Breakpoint
 <img 
  src="./images/conditional-breakpoint.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Breakpoint Options
 <img 
  src="./images/breakpoint-options.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Breakpoint Types
 <img 
  src="./images/breakpoint-types.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Java Exception Breakpoint
 <img 
  src="./images/java-exception-breakpoint.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Debug JSPs
--
### Debug JSPs - Locate URL
 <img 
  src="./images/debug-jsps-fragments.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:600px;height:auto;width:auto;" />
--
### Debug JSPs - Locate routes.xml
 <img 
  src="./images/debug-jsps-routes-xml.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Debug JSPs - Locate MVCRenderCommand Java Class
 <img 
  src="./images/debug-jsps-mvc-render-command.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:600px;height:auto;width:auto;" />
--
### Debug JSPs - Locate JSP
 <img 
  src="./images/debug-jsps-jsp.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:600px;height:auto;width:auto;" />
--
### Debug JSPs - Inspect JSP
 <img 
  src="./images/debug-jsps-jsp-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:600px;height:auto;width:auto;" />
--
### Debug JSPs - Locate generated Java Class
 <img 
  src="./images/debug-jsps-java.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:600px;height:auto;width:auto;" />
--
### Debug JSPs - Mark Directory as Generated Sources Root (1)
 <img 
  src="./images/debug-jsps-mark-directory-as.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:440px;height:auto;width:auto;" />
--
### Debug JSPs - Mark Directory as Generated Sources Root (2)
 <img 
  src="./images/debug-jsps-mark-directory-as-result.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:440px;height:auto;width:auto;" />
--
### Debug JSPs - Set breakpoint
 <img 
  src="./images/debug-jsps-set-breakpoint.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Debug JSPs - Debug as usual
 <img 
  src="./images/debug-jsps-debugger.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git
--
### Git Tool Window
 <img 
  src="./images/git.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Diff
 <img 
  src="./images/git-diff.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Select Branch
 <img 
  src="./images/git-select-branch.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Select Commits
 <img 
  src="./images/git-select-commits.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Chery Pick
 <img 
  src="./images/git-cherry-pick.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Conflicts
 <img 
  src="./images/git-conflicts.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Merge
 <img 
  src="./images/git-merge.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Interactive Rebase
 <img 
  src="./images/git-interactive-rebase.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Rebasing Commits (1)
 <img 
  src="./images/git-rebasing-commits-1.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Rebasing Commits (2)
 <img 
  src="./images/git-rebasing-commits-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show History for Selection (1)
 <img 
  src="./images/git-show-history-for-selection.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show History for Selection (2)
 <img 
  src="./images/git-show-history-for-selection-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show History for Selection (3)
 <img 
  src="./images/git-show-history-for-selection-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show History for Selection (4)
 <img 
  src="./images/git-show-history-for-selection-4.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Annotate with Git Blame (1)
 <img 
  src="./images/git-annotate-with-git-blame.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Annotate with Git Blame (2)
 <img 
  src="./images/git-annotate-with-git-blame-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Annotate with Git Blame (3)
 <img 
  src="./images/git-annotate-with-git-blame-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Paths Affected in Revision (1)
 <img 
  src="./images/git-paths-affected-in-revision.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Paths Affected in Revision (2)
 <img 
  src="./images/git-paths-affected-in-revision-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show Repository at Revision (1)
 <img 
  src="./images/git-show-repository-at-revision.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Git Show Repository at Revision (2)
 <img 
  src="./images/git-show-repository-at-revision-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database
--
### Database - New Data Source
 <img 
  src="./images/database-new-data-source.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - New Mysql Data Source 
 <img 
  src="./images/database-new-data-source-mysql.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Tables
 <img 
  src="./images/database-tables.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Table Keys & Indexes
 <img 
  src="./images/database-table-keys-and-indexes.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Table Edit Data
 <img 
  src="./images/database-table-edit-data.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Transpose (1)
 <img 
  src="./images/database-table-edit-data-transpose.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Transpose (2)
 <img 
  src="./images/database-table-edit-data-transpose-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Edit Value
 <img 
  src="./images/database-table-edit-value.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Preview Pending Changes & Submit
 <img 
  src="./images/database-table-edit-value-preview-pending-changes.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - New Query Console
 <img 
  src="./images/database-new-query-console.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Autocomplete
 <img 
  src="./images/database-autocomplete.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - View As... (Table / Tree / Text)
 <img 
  src="./images/database-view-as-table-tree-text.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - View As Tree
 <img 
  src="./images/database-view-as-tree.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Set highlighting language
 <img 
  src="./images/database-set-highlighting-language.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:750px;height:auto;width:auto;" />
--
### Database - Set highlighting language JSON
 <img 
  src="./images/database-set-highlighting-language-json.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Structure View
 <img 
  src="./images/database-grid-cell-editor-text-field-structure.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Maximize
 <img 
  src="./images/database-grid-cell-editor-text-field-maximize.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Submit
 <img 
  src="./images/database-grid-cell-editor-text-field-submit.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Submit Output
 <img 
  src="./images/database-grid-cell-editor-text-field-submit-output.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Compare cells
 <img 
  src="./images/database-compare-cells.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Database - Compare cells Diff View
 <img 
  src="./images/database-compare-cells-diff-view.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:920px;max-width:800px;height:auto;width:auto;" />
--
### Shortcuts
--
### Before diving into Shortcuts
- Finding a shortcut
- Customizing shortcuts
- "Key Promoter X" plugin
- Productivity guide
- Keymap Reference
--
### Keymap
 <img 
  src="./images/shortcuts-keymap.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Find Shortcut by Action
 <img 
  src="./images/shortcuts-find-shortcut.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Find Action by Shortcut (1)
 <img 
  src="./images/shortcuts-find-shortcut-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Find Action by Shortcut (2)
 <img 
  src="./images/shortcuts-find-shortcut-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Create your Keymap (1)
 <img 
  src="./images/shortcuts-keymap-duplicate.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Create your Keymap (2)
 <img 
  src="./images/shortcuts-keymap-name.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Customize Shortcut (1)
 <img 
  src="./images/shortcuts-customize.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Customize Shortcut (2)
 <img 
  src="./images/shortcuts-customize-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Customize Shortcut (3)
 <img 
  src="./images/shortcuts-customize-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Customize Shortcut (4)
 <img 
  src="./images/shortcuts-customize-4.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Key Promoter X Plugin (1)
 <img 
  src="./images/shortcuts-key-promoter-x.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Key Promoter X Plugin (2)
 <img 
  src="./images/shortcuts-key-promoter-x-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Productivity Guide
 <img 
  src="./images/productivity-guide.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Help > Keymap Reference
 <img 
  src="./images/shortcuts-keymap-reference.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:520px;max-width:800px;height:auto;width:auto;" />
--
### Diving into Shortcuts
- Searching
- Tool Windows & Tabs
- Navigating
- Code completion & Postfix Code completion
- Moving caret
- Selecting Code
- Working with lines
- Multicaret
- Working with changes
- Refactoring
- Debugging
--
### Diving into Shortcuts (Disclaimer)
- The shortcuts displayed in the next slides are customized
- Goal: Minimize finger movement 
- Approach: Use j, k, l, i as LEFT, DOWN, RIGHT, UP 
- Check the Keymap Reference or use "Find Shortcut by Action" for their default value
- Feel free to try them out, learn the default ones or define your own
--
### Shortcuts - Searching
- ⇧ ⌘ A Find Action
- Double ⇧ Search Everywhere
- ⌘ f Find in Editor
- ⌘ r Replace in Editor
- ⌘ g Find next
- ⌘ ⇧ g Find previous
- ⇧ ⌘ f Find in Path
- ⇧ ⌘ r Replace in Path
- in project / module /directory / scope (e.g: production files)
-- 
### Shortcuts - Tool Windows & Tabs (1)
- ⌘ º Show/Hide Debug Tool Window
- ⌘ 1 Show/Hide Project Tool window
- ⌘ 2 Show/Hide local changes
- ⌘ 8 Show/Hide Database Tool Window
- ⌘ 7 Show/Hide Structure Tool Window
- ⌘ 8 Show/Hide Pull Requests Window
- ⌘ 9 Show/Hide Git Tool Window
--
### Shortcuts - Tool Windows & Tabs (2)
- ⌘ 3 Select Tab #1 
- ⌘ 4 Select Tab #2 
- ⌘ 5 Select Tab #3 
- ⌘ ñ Next Tab 
- ⌘ ⇧ ñ Previous Tab 
- ⌘ m Maximize Tool Window
- ⌃ ⌥ ⌘ m Hide All Tool Windows
- ⎋ Focus editor
--
### Shortcuts - Navigating
- ⌘ e Recent Files
- ⌘ e Recent Edited Files
- ⇧ ⌘ e Recent Locations
- ⇧ ⌘ e Recent Edited Locations
- ⌘ ↓ Edit source / view source
- ⌥ ⌘ j Navigate back
- ⌥ ⌘ l Navigate forward
--
### Shortcuts - Code completion (1)
- ⇧ ⌘ ⏎ Complete current statement
- ⌃ Space Basic code completion (the name of any class, method or variable)
- ⌃ ⇧ Space Smart code completion (filters the list of methods and variables by expected type)
--
### Shortcuts - Code completion (2)
- Press multiple times: Some actions in IntelliJ IDEA provide more results when you execute them multiple times
⌃ Space on a part of a field, parameter, or variable declaration, it suggests
- 1s time: names depending on the item type within the current scope 
- 2nd time: classes available through module dependencies 
- 3rd time: suggestions will include the whole project
--
### Shortcuts - Postfix code completion
- .var
- .if
- .for
- .fori
- .not
- ...
--
### Shortcuts - Moving caret (1)
- ⌃ i Up
- ⌃ k Down
- ⌃ l Right
- ⌃ j Left
- ⌥ i Up
- ⌥ k Down
- ⌥ l Move caret to previous word
- ⌥ j Move caret to next word
--
### Shortcuts - Moving caret (2)
- ⌘ i Page up
- ⌘ k Page down
- ⌘ l Move caret to line end
- ⌘ j Move caret to line start
- ⌃ e Navigate to next highlighted error
- ⌃ o Next edit location
- ⌃ u Last edit location
- ⌥ o Move caret forward a paragraph
- ⌥ u Move caret backward a paragraph
- ⌘ u Go to line:column
- ⌃ m Move caret to matching brace
--
### Shortcuts - Moving caret (3)
- ⌥ n Backspace
- ⌥ ⇧ n Delete
--
### Shortcuts - Selecting code
- ⇧ ⌥ i Extend Selection
- ⇧ ⌥ k Shrink Selection
- ⌃ ⇧ l Right with selection
- ⌃ ⇧ j Left with selection 
- ⌥ ⇧ l Move caret to previous word with selection
- ⌥ ⇧ j Move caret to next word with selection
- ⌘ ⇧ l Move caret to line end with selection
- ⌘ ⇧ j Move caret to line start with selection
--
### Shortcuts - Working with lines
- ⌘ d Duplicate line
- ⌘ n Delete line
- ⌃ ⇧ j Join lines
- ⇧ ⌘ ↑ Move statement up
- ⇧ ⌘ ↓ Move statement down
- ⌘ - Comment with Line Comment
--
### Shortcuts - Multicaret
- ⌃ ⇧ ↑ Clone Caret Above
- ⌃ ⇧ ↓ Clone Caret below
- ⌥ g Add Selection for Next Occurrence
--
### Shortcuts - Working with changes
- ⌘ d Show diff
- ⌃ ⌥ k Navigate to next change
- ⌃ ⌥ i Navigate to previous change
--
### Shortcuts - Refactoring
- ⌃ v Introduce variable
- ⌥ ⇧ n Inline variable
- Change signature
--
### Shortcuts - Debugging
- ⌃ ⌥ ⌘ o Resume program
- ⌃ ⌥ ⌘ L Step over
- ⌃ ⌥ ⌘ k Step into
- ⌃ ⌥ ⌘ i Step out
- ⌃ ⌥ ⌘ c Run to cursor
- ⌃ ⌥ ⌘ , Evaluate expression
- ⌃ ⌥ ⌘ b View breakpoints
- ⌃ ⌥ b Toggle line breakpoint
--
### Useful settings
- Toggle Show whitespaces
- Configure editor to display always text centered
- Don't show tabs
- Configure a settings repository
- Memory tuning (toolbox)
--
### Toggle Show Whitespaces (1)
<img 
  src="./images/settings-toggle-whitespaces.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Toggle Show Whitespaces - On (2)
<img 
  src="./images/settings-show-whitespaces-on.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Toggle Show Whitespaces - Off (3)
<img 
  src="./images/settings-show-whitespaces-off.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure editor to display always text centered (1)
- Registry...
<img 
  src="./images/settings-registry.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
- editor.distraction.free.mode
<img 
  src="./images/settings-registry-editor-distraction-free-mode.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure editor to display always text centered (2)
<img 
  src="./images/settings-editor-text-centered.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Don't show tabs
<img 
  src="./images/settings-no-tabs.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure a settings repository (1)
<img 
  src="./images/settings-repository.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure a settings repository (2)
<img 
  src="./images/settings-repository-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure a settings repository (3)
<img 
  src="./images/settings-repository-3.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure a settings repository (4)
<img 
  src="./images/settings-repository-4.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Configure a settings repository (5)
<img 
  src="./images/settings-repository-5.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Increasing maximum heap
- Can be changed through the toolbox
<img 
  src="./images/maximum-heap.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Viewing memory used
- Memory used and maximum heap available
<img 
  src="./images/memory.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Useful plugins
- Key Promoter
- String Manipulation
- Co-Author
--
### Plugins - String Manipulation (1)
- Case switching
- Sorting
- Filtering
- Incrementing
- Aligning to columns
- Grepping
- Escaping
- Encoding
--
### Plugins - String Manipulation (2)
<img 
  src="./images/plugins-string-manipulation-1.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### Plugins - String Manipulation (3)
<img 
  src="./images/plugins-string-manipulation-2.png" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--
### IJ (your best friend in Liferay)
https://github.com/holatuwol/liferay-intellij

Script that generates all the IML files, library descriptors, and the modules.xml file needed to have a complete Liferay project that successfully resolves imports in JSPs and Java files across the 1000+ modules in Liferay.
--
### IJ - Setup
```
git clone git@github.com:holatuwol/liferay-intellij.git
```

Add function to .bashrc or functions.zsh
```
ij() {
  <IJ_CLONE_PATH>/intellij "$@"
}
```
--
### IJ - Usage
Change directory to liferay-portal

```
cd <path-to-liferay-portal>
```

To generate the IntelliJ project after `ant all`
```
ij
```

To generate IML files for a new module you add later on
```
ij <path_to_new_module>
```
--
### Useful links
- [Mastering keybarod shortcuts](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html)
- [Top 15 IntelliJ IDEA shortcuts](https://www.youtube.com/watch?v=QYO5_riePOQ)
- [Auto completing code](https://www.jetbrains.com/help/idea/auto-completing-code.html)
- [Postfix Completion](https://www.jetbrains.com/idea/guide/tips/postfix-completion/)
- [Increasing Memory Heap](https://www.jetbrains.com/help/idea/increasing-memory-heap.html)
- [Settings Repository](https://www.jetbrains.com/help/idea/sharing-your-ide-settings.html#settings-repository)
- [About the IntelliJ Modules Setup Script](https://github.com/holatuwol/liferay-intellij/blob/master/ABOUT.rst)
--
### Thank you!
<img 
  src="./images/thank-you.png" 
  alt="Thank you" 
  style="margin-left:auto;margin-right:auto;display:block;max-height:470px;max-width:800px;height:auto;width:auto;" />
--