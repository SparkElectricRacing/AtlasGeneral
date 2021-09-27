## Components

**Display:** MConn 7 from [MRS]. ---- \[[MRS Brochure]\]

**Motor:** 228 from [Emrax]. ---- \[[228 TchnclSpecs]\] -- \[[228 Manual]\]

**Motor Controller:** emDrive500 from [Emsiso]. ---- \[[500 Datasheet]\] -- \[[500 Manual]\]

**BMS**: Orion BMS 2 + Thermistor Expansion Pack --- \[[Orion Downloads]\]

**Isometer**: ir155-3204 from [Bender]. ---- \[[Iso Datasheet]\] -- \[[Iso QuickStart]\]

**Auxiliaries**: idk (throttle, horn)



[MRS]: https://www.mrs-electronics.com/products/detail/display-mconn-7#
[MRS Brochure]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7048743/MConn7i-display-brochure.pdf
[Emrax]: https://emrax.com/e-motors/emrax-228/
[228 TchnclSpecs]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148439/emrax_228_technical_data_table_graphs_5.4.pdf
[228 Manual]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148440/manual_for_emrax_motors_version_5.4.pdf
[Emsiso]: https://www.emdrive-mobility.com/portfolio/emdrive-500/
[500 Datasheet]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148452/emDrive_500_datasheet_V2_6.pdf
[500 Manual]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148449/emDrive.User.Manual_v2_2.pdf
[Orion Downloads]: http://www.orionbms.com/resources/
[Bender]: https://www.bender.de/en/products/insulation-monitoring/isometer_ir155-3203ir155-3204
[Iso Datasheet]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148433/IR155-32xx-V004_D00115_D_XXEN.Datasheet.pdf
[Iso Quickstart]: https://github.com/SparkElectricRacing/AtlasGeneral/files/7148432/IR155-32xx-V004_D00115_D_XXEN.Quick.Start.pdf


Test

<!-- saved from url=(0078)https://www.orionbms.com/tools/wiring.php?cell_count=28&fuse_position%5B%5D=15 -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"></head><body><header><title>Orion BMS Wiring Diagram Generator</title></header>

<script>
	function clearMulti(id)
	{
	    var i;
	    var select = document.getElementById(id);
	    for(i=0;i<select.options.length;i++)
	    {
	        select.options[i].selected=false;
	    }
	}

	function ClearOptions(id)
	{
		document.getElementById(id).options.length = 0;
	}
</script>

<br>
<center><img src="./Orion BMS Wiring Diagram Generator_files/logo.jpg"></center><br><br>
<font color="red"><b>DISCLAIMER:</b></font> This wiring diagram generator is intended to be used as a guide for connecting an Orion BMS to a battery pack.<br>
Since there may be wiring considerations that this tool cannot anticipate, always read through the full <a href="http://www.orionbms.com/manuals/wiring">wiring manual</a> and verify the diagram<br>
before wiring the battery pack.
<br><br>

<form action="https://www.orionbms.com/tools/wiring.php">
<table>
<tbody><tr>
<td><b>Cells in Series:</b></td><td>
<select width="100%" style="width: 100%" name="cell_count">
<option>4</option>
<option selected="selected">28</option>
<option>180</option>
</select>
<!--<input type="text" name="cell_count" value="28" />-->
</td>
<td>Select the number of cells in series in the battery pack.</td>
</tr>
<tr><td><br></td></tr>
<tr>
<td><b>Fuse / Safety<br> Disconnects:</b></td><td>
<select size="10" name="fuse_position[]" id="fuse_list" multiple="multiple">
<option value="5">4 / 5</option>
<option value="15" selected="selected">14 / 15</option>
<option value="180">179 / 180</option>
</select>
<br><input type="button" onclick="clearMulti(&#39;fuse_list&#39;);" value="Clear" style="width:100%">
</td>
<td>Indicate the location fuses or safety disconnects that are wired between cells in the battery pack (if any are used).
<br><br>Note: Cell #1 is the negative-most cell.
<br><br>Control + click to select multiple items
</td>
<!--<input type="text" name="fuse_position" value="Array" /></td>-->
</tr><tr><td><br></td></tr>
<tr>
<td><b>Long Cables:</b></td>
<td>
<script>
$("select[multiple] option").mousedown(function(){
   var $self = $(this);
   
   if ($self.attr("selected"))
       $self.attr("selected", "");
   else
       $self.attr("selected", "selected");
   return false;
});
</script>
<br><input type="button" onclick="clearMulti(&#39;busbar_list&#39;);" value="Clear" style="width:100%">
</td>
<td>Indicate the location of long cables between cells (generally cables longer than 3ft).
<br><br>Note: Cell #1 is the negative-most cell.
<br><br>Control + click to select multiple items
</td>
<!--<input type="text" name="busbar_position" value=""/>-->
</tr>
<tr>
<td colspan="2"><br><center><input type="submit" value="Generate Diagram"></center></td>
</tr>
</tbody></table>
</form> 
<br><big><big><big><b><center>Recommended BMS Size: 48-S Cell Orion BMS</center></b></big></big></big><br><br>
Diagram Legend<table border="1"><tbody><tr><td>
<span style="vertical-align:super; font-size:small;">Harness #</span><b>Cell #</b></td></tr></tbody></table>
<br><table><tbody><tr><td colspan="20"><center><b>Connector #1</b></center></td></tr>
<tr></tr><tr><td colspan="6"><center>Group 3</center></td><td>&nbsp;</td><td colspan="6"><center>Group 2</center></td><td>&nbsp;</td><td colspan="6"><center>Group 1</center></td></tr><tr>
<td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">36</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">35</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">34</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">33</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">32</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">31</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">30</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">29</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">28</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">27</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">26</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">25</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color:#484848;"><font color="white"><span style="vertical-align:super; font-size:small;">25</span><b> N/A</b></font></td></tr><tr><td><span style="vertical-align:super; font-size:small;">&nbsp;&nbsp;&nbsp;</span><b> N/A</b></td></tr></tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">24</span><b> 14</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">23</span><b> 14</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">22</span><b> 14</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">21</span><b> 14</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">20</span><b> 14</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">19</span><b> 14</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">18</span><b> 14</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">17</span><b> 13</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">16</span><b> 12</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">15</span><b> 11</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">14</span><b> 10</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">13</span><b> 9</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: #484848;"><font color="white"><span style="vertical-align:super; font-size:small;">13</span><b> 9-</b></font></td></tr><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">12</span><b> 8</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">11</span><b> 8</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">10</span><b> 8</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">9</span><b> 8</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">8</span><b> 8</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">7</span><b> 7</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">6</span><b> 6</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">5</span><b> 5</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">4</span><b> 4</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">3</span><b> 3</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">2</span><b> 2</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">1</span><b> 1</b></td></tr>
<tr><td width="70" style="background-color:#484848;"><font color="white"><span style="vertical-align:super; font-size:small;">1</span><b> 1-</b></font></td></tr></tbody></table></td></tr></tbody></table><br><table><tbody><tr><td colspan="20"><center><b>Connector #2</b></center></td></tr>
<tr></tr><tr><td colspan="6"><center>Group 6</center></td><td>&nbsp;</td><td colspan="6"><center>Group 5</center></td><td>&nbsp;</td><td colspan="6"><center>Group 4</center></td></tr><tr>
<td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">36</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">35</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">34</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">33</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">32</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">31</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">30</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">29</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">28</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">27</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">26</span><b> N/A</b></td></tr>
<tr><td width="70" style="background-color: yellow;"><span style="vertical-align:super; font-size:small;">25</span><b> N/A</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color:#484848;"><font color="white"><span style="vertical-align:super; font-size:small;">25</span><b> N/A</b></font></td></tr><tr><td><span style="vertical-align:super; font-size:small;">&nbsp;&nbsp;&nbsp;</span><b> N/A</b></td></tr></tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">24</span><b> 28</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">23</span><b> 28</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">22</span><b> 28</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">21</span><b> 28</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">20</span><b> 28</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">19</span><b> 28</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">18</span><b> 28</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">17</span><b> 27</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">16</span><b> 26</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">15</span><b> 25</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">14</span><b> 24</b></td></tr>
<tr><td width="70" style="background-color: red;"><span style="vertical-align:super; font-size:small;">13</span><b> 23</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: #484848;"><font color="white"><span style="vertical-align:super; font-size:small;">13</span><b> 23-</b></font></td></tr><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">12</span><b> 22</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">11</span><b> 22</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">10</span><b> 22</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">9</span><b> 22</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">8</span><b> 22</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">7</span><b> 21</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">6</span><b> 20</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">5</span><b> 19</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">4</span><b> 18</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">3</span><b> 17</b></td></tr>
<tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">2</span><b> 16</b></td></tr>
</tbody></table></td><td><table border="1"><tbody><tr><td width="70" style="background-color: orange;"><span style="vertical-align:super; font-size:small;">1</span><b> 15</b></td></tr>
<tr><td width="70" style="background-color:#484848;"><font color="white"><span style="vertical-align:super; font-size:small;">1</span><b> 15-</b></font></td></tr></tbody></table></td></tr></tbody></table><br><center><img src="./Orion BMS Wiring Diagram Generator_files/connector.jpg"></center><br>

</body></html>
