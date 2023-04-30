Download Link: https://assignmentchef.com/product/solved-cs220-lab3-combinational-logic-and-alu
<br>
<strong>Lab     #3       (Combinational      Logic  and     ALU)   </strong>

Name:______________________

Date:______________________              <strong><u>Converting  between      Octal  and     Decimal        Numbers</u></strong><strong>            </strong>

<table width="623">

 <tbody>

  <tr>

   <td colspan="2" width="623">1. Convert           <strong>1337</strong><sub>8</sub> to            decimal (base     10)Use sum       of            expansion           of            products              (don’t   skip        steps!)</td>

  </tr>

  <tr>

   <td colspan="2" width="623"> </td>

  </tr>

  <tr>

   <td colspan="2" width="623">2. Convert           <strong>71</strong><sub>10</sub>      to            octal      (base     8)Use the         Double-Dabble method of            successive           divsion</td>

  </tr>

  <tr>

   <td colspan="2" width="623"> </td>

  </tr>

  <tr>

   <td width="312">3. What                file          permissions        does      the         octal      number        <strong>5</strong>             exhibit?</td>

   <td width="311">4. What                file          permissions        does      the         octal      number        <strong>3</strong>             exhibit?</td>

  </tr>

  <tr>

   <td width="312"> </td>

   <td width="311"> </td>

  </tr>

 </tbody>

</table>

<strong>            </strong>

<h1>Converting   between      Hexadecimal           and     Decimal        Numbers</h1>

<table width="623">

 <tbody>

  <tr>

   <td width="623">5. Convert           <strong>AC34D1</strong><sub>16</sub>       to            decimal (base     10)Use sum       of            expansion           of            products              (don’t   skip        steps!)</td>

  </tr>

  <tr>

   <td width="623"> </td>

  </tr>

  <tr>

   <td width="623">6. Convert           <strong>365</strong><sub>10</sub>   to            hexadecimal      (base     16)Use the         Double-Dabble method of            successive           divsion</td>

  </tr>

  <tr>

   <td width="623"> </td>

  </tr>

 </tbody>

</table>




<h1>Adding          Signed           Binary           Numbers      (with  Two’s Complement)</h1>

<table width="623">

 <tbody>

  <tr>

   <td width="623">7. Add   -8            +             5              in            4-digit   binary.First               convert to            Two’s    Complement     binary,  then      compute              the        sum. </td>

  </tr>

  <tr>

   <td width="623"> </td>

  </tr>

 </tbody>

</table>




<h1>Half    Adder (Two  Inputs)          Design</h1>

<table width="638">

 <tbody>

  <tr>

   <td colspan="2" width="638">8. Write                the         Boolean               function               for          the         outputs (sum      and        carry).                   Use        K-maps if             needed.               Then      write     the         HDL        code.</td>

  </tr>

  <tr>

   <td rowspan="2" width="340"> </td>

   <td width="299">sum(a,  b)            =   carry(a, b)            =</td>

  </tr>

  <tr>

   <td width="299">CHIP      HalfAdder           {IN           a,                b;OUT       sum,                carry; PARTS:         }</td>

  </tr>

 </tbody>

</table>

<strong>            </strong>

<strong>            </strong>

<h1>Full     Adder (Three           Input) Design</h1>

<table width="638">

 <tbody>

  <tr>

   <td colspan="2" width="638">9. Write                the         Boolean               function               for          the         outputs (sum      and        carry).                   Use        K-maps if             needed.               Then      write     the         HDL        code.</td>

  </tr>

  <tr>

   <td rowspan="2" width="337"> </td>

   <td width="301"> sum(a,  b,            c)            =  carry(a, b,            c)            =</td>

  </tr>

  <tr>

   <td width="301">CHIP      FullAdder            {IN           a,                b,            c;OUT       sum,                carry; PARTS:         }</td>

  </tr>

 </tbody>

</table>




<h1>Implementing the     ALU    Design           (with  signed           two’s complement    numbers)</h1>




<table width="668">

 <tbody>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">0                                                                              <strong>                </strong></td>

   <td width="81"><strong>“1010”                                  </strong>-6</td>

   <td width="84"><strong>“0001”                                  </strong>1</td>

   <td width="63"> </td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">1</td>

   <td width="78"><strong>“1010”  </strong></td>

   <td width="107"><strong>“0001”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69">1</td>

   <td width="81"><strong>“0000”  </strong></td>

   <td width="84"><strong>                </strong></td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69">0</td>

   <td width="81"><strong>“0000”  </strong></td>

   <td width="84"><strong>                </strong></td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69">1</td>

   <td width="81"> </td>

   <td width="84"><strong>“0000”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69">0</td>

   <td width="81"> </td>

   <td width="84"><strong>“0000”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69">1</td>

   <td colspan="2" width="165"><strong>“0000”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69">0</td>

   <td colspan="2" width="165"><strong>“0000”  [</strong>0]<strong>          </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">-1</td>

   <td width="81"><strong>“1010”  </strong></td>

   <td width="84"><strong>“0001”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">x</td>

   <td width="78"><strong>“0100”  </strong></td>

   <td width="107"><strong>“0101”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td colspan="2" width="165"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td colspan="2" width="165"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

 </tbody>

</table>










<table width="668">

 <tbody>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">y</td>

   <td width="81"><strong>“1010”  </strong></td>

   <td width="84"><strong>“0011”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">!x</td>

   <td width="78"><strong>“1010”  </strong></td>

   <td width="107"><strong>“0101”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">!y</td>

   <td width="81"><strong>“1010”  </strong></td>

   <td width="84"><strong>“0101”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">“-x”</td>

   <td width="78"><strong>“0010”  </strong></td>

   <td width="107"><strong>“1000”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">“-y”</td>

   <td width="81"><strong>“1010”  </strong></td>

   <td width="84"><strong>“0001”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">x+1</td>

   <td width="78"><strong>“0001”  </strong></td>

   <td width="107"><strong>“0001”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">y+1</td>

   <td width="81"><strong>“1010”  </strong></td>

   <td width="84"><strong>“1111”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">x-1</td>

   <td width="78"><strong>“0110”  </strong></td>

   <td width="107"><strong>“0001”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">y-1</td>

   <td width="81"><strong>“0001”  </strong></td>

   <td width="84"><strong>“1111”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">x+y</td>

   <td width="78"><strong>“0010”  </strong></td>

   <td width="107"><strong>“0101”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

 </tbody>

</table>




<table width="668">

 <tbody>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">x-y</td>

   <td width="81"><strong>“0111”  </strong></td>

   <td width="84"><strong>“0010”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">y-x</td>

   <td width="78"><strong>“1101”  </strong></td>

   <td width="107"><strong>“1111”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"> </td>

   <td width="69"> </td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"> </td>

   <td width="71"> </td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f(x,y)                =             </strong></td>

   <td width="69">x&amp;y</td>

   <td width="81"><strong>“1011”  </strong></td>

   <td width="84"><strong>“1000”  </strong></td>

   <td width="63"><strong>                </strong></td>

   <td width="57"><strong>f(x,y)                =             </strong></td>

   <td width="71">x|y</td>

   <td width="78"><strong>“1111”  </strong></td>

   <td width="107"><strong>“1010”  </strong></td>

  </tr>

  <tr>

   <td width="58"><strong>zx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>nx                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>nx                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>zy                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>zy                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>ny                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>ny                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>f                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>f                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

  <tr>

   <td width="58"><strong>no                =             </strong></td>

   <td width="69"><strong>                </strong></td>

   <td width="81"> </td>

   <td width="84"> </td>

   <td width="63"> </td>

   <td width="57"><strong>no                =             </strong></td>

   <td width="71"><strong>                </strong></td>

   <td width="78"> </td>

   <td width="107"> </td>

  </tr>

 </tbody>

</table>


