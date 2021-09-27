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
<option>5</option>
<option>6</option>
<option>7</option>
<option>8</option>
<option>9</option>
<option>10</option>
<option>11</option>
<option>12</option>
<option>13</option>
<option>14</option>
<option>15</option>
<option>16</option>
<option>17</option>
<option>18</option>
<option>19</option>
<option>20</option>
<option>21</option>
<option>22</option>
<option>23</option>
<option>24</option>
<option>25</option>
<option>26</option>
<option>27</option>
<option selected="selected">28</option>
<option>29</option>
<option>30</option>
<option>31</option>
<option>32</option>
<option>33</option>
<option>34</option>
<option>35</option>
<option>36</option>
<option>37</option>
<option>38</option>
<option>39</option>
<option>40</option>
<option>41</option>
<option>42</option>
<option>43</option>
<option>44</option>
<option>45</option>
<option>46</option>
<option>47</option>
<option>48</option>
<option>49</option>
<option>50</option>
<option>51</option>
<option>52</option>
<option>53</option>
<option>54</option>
<option>55</option>
<option>56</option>
<option>57</option>
<option>58</option>
<option>59</option>
<option>60</option>
<option>61</option>
<option>62</option>
<option>63</option>
<option>64</option>
<option>65</option>
<option>66</option>
<option>67</option>
<option>68</option>
<option>69</option>
<option>70</option>
<option>71</option>
<option>72</option>
<option>73</option>
<option>74</option>
<option>75</option>
<option>76</option>
<option>77</option>
<option>78</option>
<option>79</option>
<option>80</option>
<option>81</option>
<option>82</option>
<option>83</option>
<option>84</option>
<option>85</option>
<option>86</option>
<option>87</option>
<option>88</option>
<option>89</option>
<option>90</option>
<option>91</option>
<option>92</option>
<option>93</option>
<option>94</option>
<option>95</option>
<option>96</option>
<option>97</option>
<option>98</option>
<option>99</option>
<option>100</option>
<option>101</option>
<option>102</option>
<option>103</option>
<option>104</option>
<option>105</option>
<option>106</option>
<option>107</option>
<option>108</option>
<option>109</option>
<option>110</option>
<option>111</option>
<option>112</option>
<option>113</option>
<option>114</option>
<option>115</option>
<option>116</option>
<option>117</option>
<option>118</option>
<option>119</option>
<option>120</option>
<option>121</option>
<option>122</option>
<option>123</option>
<option>124</option>
<option>125</option>
<option>126</option>
<option>127</option>
<option>128</option>
<option>129</option>
<option>130</option>
<option>131</option>
<option>132</option>
<option>133</option>
<option>134</option>
<option>135</option>
<option>136</option>
<option>137</option>
<option>138</option>
<option>139</option>
<option>140</option>
<option>141</option>
<option>142</option>
<option>143</option>
<option>144</option>
<option>145</option>
<option>146</option>
<option>147</option>
<option>148</option>
<option>149</option>
<option>150</option>
<option>151</option>
<option>152</option>
<option>153</option>
<option>154</option>
<option>155</option>
<option>156</option>
<option>157</option>
<option>158</option>
<option>159</option>
<option>160</option>
<option>161</option>
<option>162</option>
<option>163</option>
<option>164</option>
<option>165</option>
<option>166</option>
<option>167</option>
<option>168</option>
<option>169</option>
<option>170</option>
<option>171</option>
<option>172</option>
<option>173</option>
<option>174</option>
<option>175</option>
<option>176</option>
<option>177</option>
<option>178</option>
<option>179</option>
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
<option value="6">5 / 6</option>
<option value="7">6 / 7</option>
<option value="8">7 / 8</option>
<option value="9">8 / 9</option>
<option value="10">9 / 10</option>
<option value="11">10 / 11</option>
<option value="12">11 / 12</option>
<option value="13">12 / 13</option>
<option value="14">13 / 14</option>
<option value="15" selected="selected">14 / 15</option>
<option value="16">15 / 16</option>
<option value="17">16 / 17</option>
<option value="18">17 / 18</option>
<option value="19">18 / 19</option>
<option value="20">19 / 20</option>
<option value="21">20 / 21</option>
<option value="22">21 / 22</option>
<option value="23">22 / 23</option>
<option value="24">23 / 24</option>
<option value="25">24 / 25</option>
<option value="26">25 / 26</option>
<option value="27">26 / 27</option>
<option value="28">27 / 28</option>
<option value="29">28 / 29</option>
<option value="30">29 / 30</option>
<option value="31">30 / 31</option>
<option value="32">31 / 32</option>
<option value="33">32 / 33</option>
<option value="34">33 / 34</option>
<option value="35">34 / 35</option>
<option value="36">35 / 36</option>
<option value="37">36 / 37</option>
<option value="38">37 / 38</option>
<option value="39">38 / 39</option>
<option value="40">39 / 40</option>
<option value="41">40 / 41</option>
<option value="42">41 / 42</option>
<option value="43">42 / 43</option>
<option value="44">43 / 44</option>
<option value="45">44 / 45</option>
<option value="46">45 / 46</option>
<option value="47">46 / 47</option>
<option value="48">47 / 48</option>
<option value="49">48 / 49</option>
<option value="50">49 / 50</option>
<option value="51">50 / 51</option>
<option value="52">51 / 52</option>
<option value="53">52 / 53</option>
<option value="54">53 / 54</option>
<option value="55">54 / 55</option>
<option value="56">55 / 56</option>
<option value="57">56 / 57</option>
<option value="58">57 / 58</option>
<option value="59">58 / 59</option>
<option value="60">59 / 60</option>
<option value="61">60 / 61</option>
<option value="62">61 / 62</option>
<option value="63">62 / 63</option>
<option value="64">63 / 64</option>
<option value="65">64 / 65</option>
<option value="66">65 / 66</option>
<option value="67">66 / 67</option>
<option value="68">67 / 68</option>
<option value="69">68 / 69</option>
<option value="70">69 / 70</option>
<option value="71">70 / 71</option>
<option value="72">71 / 72</option>
<option value="73">72 / 73</option>
<option value="74">73 / 74</option>
<option value="75">74 / 75</option>
<option value="76">75 / 76</option>
<option value="77">76 / 77</option>
<option value="78">77 / 78</option>
<option value="79">78 / 79</option>
<option value="80">79 / 80</option>
<option value="81">80 / 81</option>
<option value="82">81 / 82</option>
<option value="83">82 / 83</option>
<option value="84">83 / 84</option>
<option value="85">84 / 85</option>
<option value="86">85 / 86</option>
<option value="87">86 / 87</option>
<option value="88">87 / 88</option>
<option value="89">88 / 89</option>
<option value="90">89 / 90</option>
<option value="91">90 / 91</option>
<option value="92">91 / 92</option>
<option value="93">92 / 93</option>
<option value="94">93 / 94</option>
<option value="95">94 / 95</option>
<option value="96">95 / 96</option>
<option value="97">96 / 97</option>
<option value="98">97 / 98</option>
<option value="99">98 / 99</option>
<option value="100">99 / 100</option>
<option value="101">100 / 101</option>
<option value="102">101 / 102</option>
<option value="103">102 / 103</option>
<option value="104">103 / 104</option>
<option value="105">104 / 105</option>
<option value="106">105 / 106</option>
<option value="107">106 / 107</option>
<option value="108">107 / 108</option>
<option value="109">108 / 109</option>
<option value="110">109 / 110</option>
<option value="111">110 / 111</option>
<option value="112">111 / 112</option>
<option value="113">112 / 113</option>
<option value="114">113 / 114</option>
<option value="115">114 / 115</option>
<option value="116">115 / 116</option>
<option value="117">116 / 117</option>
<option value="118">117 / 118</option>
<option value="119">118 / 119</option>
<option value="120">119 / 120</option>
<option value="121">120 / 121</option>
<option value="122">121 / 122</option>
<option value="123">122 / 123</option>
<option value="124">123 / 124</option>
<option value="125">124 / 125</option>
<option value="126">125 / 126</option>
<option value="127">126 / 127</option>
<option value="128">127 / 128</option>
<option value="129">128 / 129</option>
<option value="130">129 / 130</option>
<option value="131">130 / 131</option>
<option value="132">131 / 132</option>
<option value="133">132 / 133</option>
<option value="134">133 / 134</option>
<option value="135">134 / 135</option>
<option value="136">135 / 136</option>
<option value="137">136 / 137</option>
<option value="138">137 / 138</option>
<option value="139">138 / 139</option>
<option value="140">139 / 140</option>
<option value="141">140 / 141</option>
<option value="142">141 / 142</option>
<option value="143">142 / 143</option>
<option value="144">143 / 144</option>
<option value="145">144 / 145</option>
<option value="146">145 / 146</option>
<option value="147">146 / 147</option>
<option value="148">147 / 148</option>
<option value="149">148 / 149</option>
<option value="150">149 / 150</option>
<option value="151">150 / 151</option>
<option value="152">151 / 152</option>
<option value="153">152 / 153</option>
<option value="154">153 / 154</option>
<option value="155">154 / 155</option>
<option value="156">155 / 156</option>
<option value="157">156 / 157</option>
<option value="158">157 / 158</option>
<option value="159">158 / 159</option>
<option value="160">159 / 160</option>
<option value="161">160 / 161</option>
<option value="162">161 / 162</option>
<option value="163">162 / 163</option>
<option value="164">163 / 164</option>
<option value="165">164 / 165</option>
<option value="166">165 / 166</option>
<option value="167">166 / 167</option>
<option value="168">167 / 168</option>
<option value="169">168 / 169</option>
<option value="170">169 / 170</option>
<option value="171">170 / 171</option>
<option value="172">171 / 172</option>
<option value="173">172 / 173</option>
<option value="174">173 / 174</option>
<option value="175">174 / 175</option>
<option value="176">175 / 176</option>
<option value="177">176 / 177</option>
<option value="178">177 / 178</option>
<option value="179">178 / 179</option>
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
<select multiple="multiple" size="10" name="busbar_position[]" id="busbar_list">	
<option value="5">4 / 5</option>
<option value="6">5 / 6</option>
<option value="7">6 / 7</option>
<option value="8">7 / 8</option>
<option value="9">8 / 9</option>
<option value="10">9 / 10</option>
<option value="11">10 / 11</option>
<option value="12">11 / 12</option>
<option value="13">12 / 13</option>
<option value="14">13 / 14</option>
<option value="15">14 / 15</option>
<option value="16">15 / 16</option>
<option value="17">16 / 17</option>
<option value="18">17 / 18</option>
<option value="19">18 / 19</option>
<option value="20">19 / 20</option>
<option value="21">20 / 21</option>
<option value="22">21 / 22</option>
<option value="23">22 / 23</option>
<option value="24">23 / 24</option>
<option value="25">24 / 25</option>
<option value="26">25 / 26</option>
<option value="27">26 / 27</option>
<option value="28">27 / 28</option>
<option value="29">28 / 29</option>
<option value="30">29 / 30</option>
<option value="31">30 / 31</option>
<option value="32">31 / 32</option>
<option value="33">32 / 33</option>
<option value="34">33 / 34</option>
<option value="35">34 / 35</option>
<option value="36">35 / 36</option>
<option value="37">36 / 37</option>
<option value="38">37 / 38</option>
<option value="39">38 / 39</option>
<option value="40">39 / 40</option>
<option value="41">40 / 41</option>
<option value="42">41 / 42</option>
<option value="43">42 / 43</option>
<option value="44">43 / 44</option>
<option value="45">44 / 45</option>
<option value="46">45 / 46</option>
<option value="47">46 / 47</option>
<option value="48">47 / 48</option>
<option value="49">48 / 49</option>
<option value="50">49 / 50</option>
<option value="51">50 / 51</option>
<option value="52">51 / 52</option>
<option value="53">52 / 53</option>
<option value="54">53 / 54</option>
<option value="55">54 / 55</option>
<option value="56">55 / 56</option>
<option value="57">56 / 57</option>
<option value="58">57 / 58</option>
<option value="59">58 / 59</option>
<option value="60">59 / 60</option>
<option value="61">60 / 61</option>
<option value="62">61 / 62</option>
<option value="63">62 / 63</option>
<option value="64">63 / 64</option>
<option value="65">64 / 65</option>
<option value="66">65 / 66</option>
<option value="67">66 / 67</option>
<option value="68">67 / 68</option>
<option value="69">68 / 69</option>
<option value="70">69 / 70</option>
<option value="71">70 / 71</option>
<option value="72">71 / 72</option>
<option value="73">72 / 73</option>
<option value="74">73 / 74</option>
<option value="75">74 / 75</option>
<option value="76">75 / 76</option>
<option value="77">76 / 77</option>
<option value="78">77 / 78</option>
<option value="79">78 / 79</option>
<option value="80">79 / 80</option>
<option value="81">80 / 81</option>
<option value="82">81 / 82</option>
<option value="83">82 / 83</option>
<option value="84">83 / 84</option>
<option value="85">84 / 85</option>
<option value="86">85 / 86</option>
<option value="87">86 / 87</option>
<option value="88">87 / 88</option>
<option value="89">88 / 89</option>
<option value="90">89 / 90</option>
<option value="91">90 / 91</option>
<option value="92">91 / 92</option>
<option value="93">92 / 93</option>
<option value="94">93 / 94</option>
<option value="95">94 / 95</option>
<option value="96">95 / 96</option>
<option value="97">96 / 97</option>
<option value="98">97 / 98</option>
<option value="99">98 / 99</option>
<option value="100">99 / 100</option>
<option value="101">100 / 101</option>
<option value="102">101 / 102</option>
<option value="103">102 / 103</option>
<option value="104">103 / 104</option>
<option value="105">104 / 105</option>
<option value="106">105 / 106</option>
<option value="107">106 / 107</option>
<option value="108">107 / 108</option>
<option value="109">108 / 109</option>
<option value="110">109 / 110</option>
<option value="111">110 / 111</option>
<option value="112">111 / 112</option>
<option value="113">112 / 113</option>
<option value="114">113 / 114</option>
<option value="115">114 / 115</option>
<option value="116">115 / 116</option>
<option value="117">116 / 117</option>
<option value="118">117 / 118</option>
<option value="119">118 / 119</option>
<option value="120">119 / 120</option>
<option value="121">120 / 121</option>
<option value="122">121 / 122</option>
<option value="123">122 / 123</option>
<option value="124">123 / 124</option>
<option value="125">124 / 125</option>
<option value="126">125 / 126</option>
<option value="127">126 / 127</option>
<option value="128">127 / 128</option>
<option value="129">128 / 129</option>
<option value="130">129 / 130</option>
<option value="131">130 / 131</option>
<option value="132">131 / 132</option>
<option value="133">132 / 133</option>
<option value="134">133 / 134</option>
<option value="135">134 / 135</option>
<option value="136">135 / 136</option>
<option value="137">136 / 137</option>
<option value="138">137 / 138</option>
<option value="139">138 / 139</option>
<option value="140">139 / 140</option>
<option value="141">140 / 141</option>
<option value="142">141 / 142</option>
<option value="143">142 / 143</option>
<option value="144">143 / 144</option>
<option value="145">144 / 145</option>
<option value="146">145 / 146</option>
<option value="147">146 / 147</option>
<option value="148">147 / 148</option>
<option value="149">148 / 149</option>
<option value="150">149 / 150</option>
<option value="151">150 / 151</option>
<option value="152">151 / 152</option>
<option value="153">152 / 153</option>
<option value="154">153 / 154</option>
<option value="155">154 / 155</option>
<option value="156">155 / 156</option>
<option value="157">156 / 157</option>
<option value="158">157 / 158</option>
<option value="159">158 / 159</option>
<option value="160">159 / 160</option>
<option value="161">160 / 161</option>
<option value="162">161 / 162</option>
<option value="163">162 / 163</option>
<option value="164">163 / 164</option>
<option value="165">164 / 165</option>
<option value="166">165 / 166</option>
<option value="167">166 / 167</option>
<option value="168">167 / 168</option>
<option value="169">168 / 169</option>
<option value="170">169 / 170</option>
<option value="171">170 / 171</option>
<option value="172">171 / 172</option>
<option value="173">172 / 173</option>
<option value="174">173 / 174</option>
<option value="175">174 / 175</option>
<option value="176">175 / 176</option>
<option value="177">176 / 177</option>
<option value="178">177 / 178</option>
<option value="179">178 / 179</option>
<option value="180">179 / 180</option>
</select>
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
