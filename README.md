Download Link: https://assignmentchef.com/product/solved-cse101-homework-5
<br>
In this homework you have to sort all the people given in “hw4_disordered_people.txt”. You will get the sort column from the user and write the ordered people in “orderedFile.txt”.

Standart column order is as shown (items aren’t sorted):

<table width="620">

 <tbody>

  <tr>

   <td width="102">ID</td>

   <td width="94">NAME</td>

   <td width="94">SIR NAME</td>

   <td width="329">MAIL</td>

  </tr>

  <tr>

   <td width="102">4564765</td>

   <td width="94">Andria</td>

   <td width="94">MALLE</td>

   <td width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="1a7b78795a7d777b737634797577">[email protected]</a></td>

  </tr>

  <tr>

   <td width="102">246574</td>

   <td width="94">Andrea</td>

   <td width="94">DENNIS</td>

   <td width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f392919090b3949e929a9fdd909c9e">[email protected]</a></td>

  </tr>

  <tr>

   <td width="102">454</td>

   <td width="94">Angeline</td>

   <td width="94">TOWNSEND</td>

   <td width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="186c776f766b7d767c587f75797174367b7775">[email protected]</a></td>

  </tr>

  <tr>

   <td width="102">3245…..</td>

   <td width="94">Ania</td>

   <td width="94">DEAR</td>

   <td width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="690d0c0f0e0103020504070d290e04080005470a0604">[email protected]</a></td>

  </tr>

 </tbody>

</table>

The column selected by the user will be placed on the first column and the order will be made according to it. Sample:

<table width="618">

 <tbody>

  <tr>

   <td colspan="4" width="289">Give a Sort Metric (I = ID               N= NAME</td>

   <td width="94">S= SIR NAME</td>

   <td width="235">               M=MAIL): M</td>

  </tr>

  <tr>

   <td colspan="4" width="289"><u>Output file</u> will be as shown (sorted by mail):</td>

   <td rowspan="2" width="94">NAME</td>

   <td rowspan="2" width="235">SIR NAME (this line must be added)</td>

  </tr>

  <tr>

   <td colspan="2" width="173">MAIL</td>

   <td colspan="2" width="116">       ID</td>

  </tr>

  <tr>

   <td colspan="2" width="173"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="8cedeeefccebe1ede5e0a2efe3e1">[email protected]</a></td>

   <td colspan="2" width="116">4564765</td>

   <td width="94">Andria</td>

   <td width="235">MALLE</td>

  </tr>

  <tr>

   <td colspan="2" width="173"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="92f3f0f1f1d2f5fff3fbfebcf1fdff">[email protected]</a></td>

   <td colspan="2" width="116">246574</td>

   <td width="94">Andrea</td>

   <td width="235">DENNIS</td>

  </tr>

  <tr>

   <td colspan="2" width="173"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="cca8a9aaaba4a6a7a0a1a2a88caba1ada5a0e2afa3a1">[email protected]</a></td>

   <td colspan="2" width="116">       3245</td>

   <td width="94">Ania</td>

   <td width="235">DEAR</td>

  </tr>

  <tr>

   <td colspan="2" width="173"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="32465d455c41575c5672555f535b5e1c515d5f">[email protected]</a>…..</td>

   <td colspan="2" rowspan="2" width="116">       454</td>

   <td rowspan="2" width="94">Angeline</td>

   <td rowspan="2" width="235">TOWNSEND</td>

  </tr>

  <tr>

   <td colspan="2" width="173"> </td>

  </tr>

  <tr>

   <td colspan="6" width="618">Give a Sort Metric (I = ID               N= NAME            S= SIR NAME                    M=MAIL): N<u>Output file</u> will be as shown (sorted by name):</td>

  </tr>

  <tr>

   <td width="86">NAME</td>

   <td colspan="2" width="108">     ID</td>

   <td width="94">SIR NAME</td>

   <td colspan="2" width="329">MAIL                                              (this line must be added)</td>

  </tr>

  <tr>

   <td width="86">Andrea</td>

   <td colspan="2" width="108">246574</td>

   <td width="94">DENNIS</td>

   <td colspan="2" width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="127370717152757f737b7e3c717d7f">[email protected]</a></td>

  </tr>

  <tr>

   <td width="86">Andria</td>

   <td colspan="2" width="108">4564765</td>

   <td width="94">MALLE</td>

   <td colspan="2" width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="69080b0a290e04080005470a0604">[email protected]</a></td>

  </tr>

  <tr>

   <td width="86">Ania</td>

   <td colspan="2" width="108">     3245</td>

   <td width="94">DEAR</td>

   <td colspan="2" width="329"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a7c3c2c1c0cfcdcccbcac9c3e7c0cac6cecb89c4c8ca">[email protected]</a></td>

  </tr>

  <tr>

   <td width="86">Angeline……</td>

   <td colspan="5" rowspan="2" width="532">     454                        TOWNSEND       <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="a3d7ccd4cdd0c6cdc7e3c4cec2cacf8dc0ccce">[email protected]</a></td>

  </tr>

  <tr>

   <td width="86"> </td>

  </tr>

  <tr>

   <td width="86"></td>

   <td width="87"></td>

   <td width="21"></td>

   <td width="94"></td>

   <td width="94"></td>

   <td width="235"></td>

  </tr>

 </tbody>

</table>

The order of ascii table will be used in the sorting. Detailed in the next page.

Tips:

<ul>

 <li>If tou need you can use itoa function to convert integer to char array:</li>

</ul>

<a href="http://www.cplusplus.com/reference/cstdlib/itoa/">http://www.cplusplus.com/reference/cstdlib/itoa/</a>

<ul>

 <li>There is no restriction to use of c libraries.</li>

</ul>

Rules:

<ul>

 <li>Console inputs must be accept upper case character “N, M,I,S”. Can be accept lower case character “n, m, i, s”</li>

 <li>Output file name: txt</li>

 <li>Input file name is: txt</li>

 <li>Upload your files <u>only</u> in a .zip file on Moodle. The zip name should be in the same in the form of: number_name_surname (g.e. 181041001_abdullahsalih_bayraktar.zip).</li>

 <li>Zip file can contain source files with “c” and or “h” extension. No other files excluding hw4_disordered_people.txt (look at next rule).</li>

 <li><u>You can</u> add a working “hw4_disordered_people.txt” file in zip. (It is chanced because it can be possible that your homework is not finish and work only with unique input file).</li>

 <li><strong>main file name: student_id_main.c (e.g. c) </strong></li>

</ul>


