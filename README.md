# TaurusProject
TaurusProject is the multiplatform programing language project. There will be many elements and progres-steps of this.

Elements:
<ol>
  <li>Terminal</li>
    <p>The Taurus Terminal is a smal deweloper test and it has no specifed features.</p>
    <table>
      <p>List of terminal comands</p>
      <tr>
        <th>ID</th>
        <th>cmd</th>
        <th>args</th>
        <th>description</th>
      </tr>
      <tr>
        <td>0</td>
        <td>exit</td>
        <td>[VOID]</td>
        <td>calls C exit with 0 as arg</td>
      </tr>
      <tr>
        <td>1</td>
        <td>exit</td>
        <td>[code:NUM]</td>
        <td>calls C exit with code as arg</td>
      </tr>
      <tr>
        <td>2</td>
        <td>putn</td>
        <td>[n:REL]</td>
        <td>Prints number n</td>
      </tr>
      <tr>
        <td>3</td>
        <td>puts</td>
        <td>[s:STR]</td>
        <td>Prints string s</td>
      </tr>
      <tr>
        <td>4</td>
        <td>push</td>
        <td>[v:ANY]</td>
        <td>Push v to the memory stack</td>
      </tr>
      <tr>
        <td>5</td>
        <td>pop</td>
        <td>[VOID]</td>
        <td>Pop top value from the memory stack</td>
      </tr>
      <tr>
        <td>6</td>
        <td>get</td>
        <td>[VOID]</td>
        <td>Gets the top value from the memory stack and puts it to _get varible</td>
      </tr>
      <tr>
        <td>7</td>
        <td>get</td>
        <td>[id:NUM]</td>
        <td>Gets the top value from the memory stack and puts it to the index of id</td>
      </tr>
      <tr>
        <td>8</td>
        <td>index</td>
        <td>[id:NUM]</td>
        <td>Gets the value from index id and puts it to _get varible</td>
      </tr>
      <tr>
        <td>9</td>
        <td>index</td>
        <td>[id:NUM] [v:ANY]</td>
        <td>Puts the v value to the id index</td>
      </tr>
      <tr>
        <td>10</td>
        <td>pushi</td>
        <td>[v:ANY]</td>
        <td>Inits new index with v value and biggest id</td>
      </tr>
      <tr>
        <td>11</td>
        <td>popi</td>
        <td>[VOID]</td>
        <td>Deletes the biggest index</td>
      </tr>
      <tr>
        <td>12</td>
        <td>sizei</td>
        <td>[VOID]</td>
        <td>Gets size of indexed memory and puts it into _get</td>
      </tr>
      <tr>
        <td>13</td>
        <td>sizei</td>
        <td>[id:NUM]</td>
        <td>Gets size of indexed memory and puts it into index id</td>
      </tr>
      <tr>
        <td>14</td>
        <td>swapi</td>
        <td>[id1:NUM] [id2:NUM]</td>
        <td>Swaps two indexes (index id1 and index id2)</td>
      </tr>
    </table>
</ol>
