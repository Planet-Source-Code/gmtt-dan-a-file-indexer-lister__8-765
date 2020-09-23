<div align="center">

## A file indexer / lister


</div>

### Description

this list alls the files in a the current directory
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[gmtt\_dan](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/gmtt-dan.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Files](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files__8-2.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/gmtt-dan-a-file-indexer-lister__8-765/archive/master.zip)





### Source Code

<? $maindir = "." ; $mydir = opendir($maindir) ; $exclude = array( "index.php") ; while($fn = readdir($mydir)) { if ($fn == $exclude[0] || $fn == $exclude[1]) continue; echo "<br><a href='$fn'>$fn</a>"; } closedir($mydir); ?>

