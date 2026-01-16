<b>Ada industrial control widget library</b>

<p>The described here packages are provided for design high-quality industrial control widgets for Ada applications. The software is based on GtkAda, Ada bindings to GTK+ and cairo. The key features of the library:</p>
<ul>
<li>Widgets composed of transparent layers drawn by cairo;</li>
<li>Fully scalable graphics;</li>
<li>Support of time controlled refresh policy for real-time and heavy-duty applications;</li>
<li>Caching graphical operations;</li>
<li>Stream I/O support for serialization and deserialization;</li>
<li>Ready-to-use gauge, meter, oscilloscope widgets;</li>
<li>Editor widget for WYSIWYG design of complex dashboards.</li>
</ul>
<H2>Widgets gallery</H2>
<p>The widget gallery shows some examples of widgets implemented using the 
library. These are provided rather as usable samples due to variability of 
requirements on the style used in projects. The implementations are very 
straightforward and can be used as templates for customization.</p>
<H3>Gauges</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center"><img border="0" src="gtk_gauge_round_254.png" width="246" height="246" alt="gauge round 254"></td>
		<td align="center"><img border="0" src="gtk_gauge_round_270_reversed.png" width="246" height="246" alt="gauge round 270 reversed"></td>
	</tr>
	<tr>
		<td align="center"><img border="0" src="gtk_gauge_round_270.png" width="246" height="246" alt="gauge round 270"></td>
		<td align="center"><img border="0" src="gtk_gauge_round_270_inout.png" width="246" height="246" alt="gauge round 270 inout"></td>
	</tr>
	<tr>
		<td align="center"><img border="0" src="gtk_gauge_round_270_out.png" width="226" height="226" alt="gauge round 270 out"></td>
		<td align="center"><img border="0" src="gtk_gauge_round_270_60s.png" width="226" height="226" alt="gauge round 270 60s"></td>
	</tr>
</table>
<H3>Sectors and segments</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_round_180.png" width="243" height="136" alt="gauge round 180"></td>
		<td align="center">
		<img border="0" src="gtk_gauge_elliptic_180.png" width="246" height="137" alt="gauge elliptic 180"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_round_90.png" width="249" height="154" alt="gauge round 90"></td>
		<td align="center">&nbsp;</td>
	</tr>
	<tr>
		<td align="center" colspan="2">
		<img border="0" src="gtk_gauge_round_110.png" width="415" height="112" alt="gauge round 110"></td>
	</tr>
</table>
<H3>Meters</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_meter_angular_90.png" width="283" height="284" alt="meter angular 90"></td>
		<td align="center">
		<img border="0" src="gtk_meter_round_94.png" width="262" height="218" alt="meter round 94"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_meter_elliptic_90.png" width="283" height="148" alt="meter elliptic 90"></td>
		<td align="center">
		<img border="0" src="gtk_meter_round_90.png" width="283" height="148" alt="meter round 90"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_valve_round_90.png" alt="valve round 90"></td>
	</tr>
	</table>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_meter_thermo.png" width="142" height="425" alt="meter thermo"></td>
		<td align="center">
		<img border="0" src="gtk_meter_thermo_symmetric.png" width="143" height="426" alt="meter thermo symmetric"></td>
		<td align="center">
		<img border="0" src="gtk_meter_thermo_dual.png" width="142" height="426" alt="meter thermo dual"></td>
	</tr>
	</table>
<H3>Flat and rectangular</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_rectangular_70s.png" width="369" height="104" alt="gauge rectangular 70s"></td>
		<td align="center" rowspan="3">
		<img border="0" src="gtk_gauge_flat_vertical.png" width="159" height="446" alt="gauge flat vertical"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_rectangular_70s_slanted.png" width="369" height="104" alt="gauge rectangular 60s slanted"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_flat_horizontal.png" width="349" height="114" alt="gauge flat horizontal"></td>
	</tr>
</table>
<H3>Wall clocks</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_clock_imperial.png" width="243" height="244" alt="clock imperial"></td>
		<td align="center">
		<img border="0" src="gtk_clock_modern.png" width="243" height="244" alt="clock modern"></td>
	</tr>
	<tr>
		<td align="center">
		<img border="0" src="gtk_clock_classic.png" width="243" height="244" alt="clock classic"></td>
		<td align="center">&nbsp;</td>
	</tr>
</table>

<H3>Oscilloscope</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="oscilloscope-stack.png" width="450" height="659" alt="oscilloscope stack"></td>
	</tr>
	</table>

<H3>LEDs</H3>
<table border="0" cellspacing="10">
	<tr>
		<td align="center">
		<img border="0" src="gtk_gauge_led_round.png" width="231" height="43" alt="gauge led round"></td>
		<td align="center">
		<img border="0" src="gtk_gauge_led_rectangular.png" width="231" height="43" alt="gauge led rectangular"></td>
	</tr>
	</table>

Home page: https://www.dmitry-kazakov.de/ada/aicwl.htm

Changes log: https://www.dmitry-kazakov.de/ada/aicwl.htm#changes_log
