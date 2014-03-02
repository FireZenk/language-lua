Lua language support in Atom
======

Add syntax highlighting and snippets to Lua files in Atom.

Common snippets
---
| Trigger       | Name                     | Body                 |
| ------------- |--------------------------| ---------------------|
| -[            | multiline comment        | --[[ comment... ]]   |
| =[            | nested multiline comment | --[=[ comment... ]=] |
| afun          | anon function            | functionName = function (args) -- body... end |
| for           | for i=1,10               | for i = 1, 10 do -- body... end |
| fori          | for i,v in ipairs()      | for i,v in ipairs(table_name) do -- body... end |
| forp          | for k,v in pairs()       | for k,v in pairs(table_name) do -- body... end |
| fun           | function                 | function functionName (args) -- body... end |
| if            | if conditional           | if value then --body... end |
| ife           | if else conditional      | if value then --body... else --body... end |
| ifn           | if not conditional       | if not value then --body... end |
| ifne          | if not else conditional  | if not value then --body... else --body... end |
| loc           | local variable definition shortcut | local x = 1 |
| local         | local variable definition | local x = 1 |
| log           | log                      | print("logging")     |
| ltab          | local table definition   | local name = {}      |
| rep           | repeat loop shortcut     | repeat -- body... until condition |
| repeat        | repeat loop              | repeat -- body... until condition |
| req           | require shortcut         | local name = require "module" |
| require       | require                  | local name = require "module" |
| ret           | return definition shortcut | return value       |
| return        | return definition        | return value         |
| tab           | table definition         | name = {}            |
| whi           | while loop shortcut      | while condition do -- body... end |
| while         | while loop shortcut      | while condition do -- body... end |

Table function snippets
---
| Trigger       | Name                     | Body                 |
| ------------- |--------------------------| ---------------------|
| tabc          | table.concat             | table.concat(tableName, " ", start_index, end_index) |
| tabf          | table.foreach            | table.foreach(tableName, function) |
| tabi          | table.insert             | table.insert(tableName, data) |
| tabs          | table.sort               | table.sort(tableName, sortfunction) |


Author
------
__Jorge Garrido Oval__
* [https://github.com/FireZenk](https://github.com/FireZenk)


Contributors
---

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

License
------
Bigot is released under the MIT license.

>Originally [converted](http://atom.io/docs/latest/converting-a-text-mate-bundle)
from the [Lua TextMate bundle](https://github.com/textmate/lua.tmbundle).
