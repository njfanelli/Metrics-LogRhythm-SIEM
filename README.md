<p style="text-align: center;"><span style="font-size: 16pt;"><strong>LogRhythm Reporting Metrics</strong></span></p>
<p>This repository contains LogRhythm related content that is specifically focused around reporting metrics.&nbsp; The hope is to provide these files free to the community so we all can benefit from them.&nbsp; Please feel free to share any improvements to the content that is provided and I will make sure you get credit for your contributions to the community.&nbsp;</p>
<p><span style="text-decoration: underline;"><strong><span style="font-size: 12pt;">Getting Started</span></strong></span></p>
<ol>
<li>Download PowerBI here: <a href="https://powerbi.microsoft.com/en-us/downloads/">https://powerbi.microsoft.com/en-us/downloads/</a></li>
<li>Save/Download&nbsp;</li>
<li>Launch the PowerBI template file (LogRhythm Metrics v1.pbix)</li>
<li>Once in the file we&rsquo;ll need to change the data sources to point to your LogRhythm instance</li>
<li>In the ribbon click &ldquo;Edit Queries&rdquo; then select &ldquo;Data Source Settings&rdquo;</li>
</ol>
<p style="padding-left: 40px;">Change the following items:</p>
<ul>
<li style="list-style-type: none;">
<ul>
<li>Highlight 127.0.0.1;LogRhythm_Alarms
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the server address to display your Platform Manager then click &ldquo;OK&rdquo;</li>
<li>Click &ldquo;Edit Permissions&rdquo;, under Credentials select &ldquo;Edit&rdquo; and make sure Windows is selected and configuration is set to &ldquo;Use my current credentials&rdquo; then click &ldquo;Save&rdquo; followed by &ldquo;OK&rdquo;</li>
</ul>
</li>
<li>Highlight 127.0.0.1;LogRhythm_CMDB
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the server address to display your Platform Manager then click &ldquo;OK&rdquo;</li>
<li>Click &ldquo;Edit Permissions&rdquo;, under Credentials select &ldquo;Edit&rdquo; and make sure Database is selected and configuration is set to &ldquo;&lt;an account with DB access&gt;&rdquo; then click &ldquo;Save&rdquo; followed by &ldquo;OK&rdquo;</li>
</ul>
</li>
<li>Highlight 127.0.0.1;LogRhythm_LogMart
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the server address to display your Platform Manager then click &ldquo;OK&rdquo;</li>
<li>Click &ldquo;Edit Permissions&rdquo;, under Credentials select &ldquo;Edit&rdquo; and make sure Windows is selected and configuration is set to &ldquo;Use my current credentials&rdquo; then click &ldquo;Save&rdquo; followed by &ldquo;OK&rdquo;</li>
</ul>
</li>
<li>Highlight 127.0.0.1;LogRhythmEMDB
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the server address to display your Platform Manager then click &ldquo;OK&rdquo;</li>
<li>Click &ldquo;Edit Permissions&rdquo;, under Credentials select &ldquo;Edit&rdquo; and make sure Database is selected and configuration is set to &ldquo;&lt;an account with DB access&gt;&rdquo; then click &ldquo;Save&rdquo; followed by &ldquo;OK&rdquo;</li>
</ul>
</li>
<li>Highlight C:\alarmstatus.xlsx
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the file path to where you stored the alarmstatus.xlsx file</li>
</ul>
</li>
<li>Highlight C:\casestatus.xlsx
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the file path to where you stored the casestatus.xlsx file</li>
</ul>
</li>
<li>Highlight C:\prioritystatus.xlsx
<ul>
<li>Click &ldquo;Change Source&rdquo; and update the file path to where you stored the prioritystatus.xlsx file</li>
</ul>
</li>
</ul>
</li>
</ul>
<p>&nbsp;</p>
<p><span style="text-decoration: underline;"><strong><span style="font-size: 12pt;">Screenshots:</span></strong><span style="font-size: 11pt;">&nbsp;</span></span></p>
<p style="padding-left: 40px;"><span style="font-size: 11pt;"><img src="https://github.com/njfanelli/Metrics-LogRhythm-SIEM/blob/master/EXAMPLE%20-%20Main%20Dashboard.PNG" alt="Main" width="800" height="600" /></span></p>
<p style="padding-left: 40px;"><span style="font-size: 11pt;"><img src="https://github.com/njfanelli/Metrics-LogRhythm-SIEM/blob/master/EXAMPLE%20-%20Alarm%20Details.PNG" alt="Alarm" width="800" height="600" /></span></p>
<p style="padding-left: 40px;"><span style="font-size: 11pt;"><img src="https://github.com/njfanelli/Metrics-LogRhythm-SIEM/blob/master/EXAMPLE%20-%20Case%20Details.PNG" alt="Cases" width="800" height="600" /></span></p>
