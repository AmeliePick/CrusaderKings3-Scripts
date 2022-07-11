# Description
During the playing I found that if some ally called us to join them war but we decline it,
then we won't be able to join to this war later, not on any side at all.

What about situation when we have two allies which are fighting with each other but we already
cannot help anyone?

This changes should fixes the reason of this problem but not repair the situation if
you are already declined the join war offer. To fix this, open your save file,
try to find a war by the name(simply try to found it by contested title), there you
can find this line started with "called_to_war". In braces find your character ID and just remove it.
Save the file. Reload the save.

# Installation path
<table style="width:100%">
  <tr>
    <th>File</th>
    <th>Destination folder</th>
  </tr>
  <tr>
    <td>00_alliance.txt</td>
    <td>Crusader Kings III/game/common/character_interactions/</tr>
</table>
