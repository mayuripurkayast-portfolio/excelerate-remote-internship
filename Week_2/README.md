<h1 align="center">🧹 Week 2 — Data Cleaning &amp; Quality Report</h1>
<p align="center"><b>Impact Makers (Team 5)</b> &nbsp;·&nbsp; Output: <code>cleaned_dataset_final.csv</code></p>

<h2>✅ Cleaning Steps Performed</h2>
<ul>
  <li><b>Column Standardization</b> — lowercase names, spaces → underscores</li>
  <li><b>Placeholder Consolidation</b> — "Unknown" → Null (NaN)</li>
  <li><b>Datetime Casting</b> — proper date formats + forward-fill</li>
  <li><b>Duplicate Removal</b> — purged redundant records</li>
  <li><b>Text Sanitization</b> — trimmed extra whitespace in text columns</li>
</ul>

<h2>📈 Before vs After</h2>
<table>
  <tr><th>Metric</th><th>Before</th><th>After</th></tr>
  <tr><td>Records</td><td>7,543</td><td>7,543 (0 duplicates)</td></tr>
  <tr><td>Missing Values</td><td>371,657</td><td>366,711</td></tr>
</table>

<h2>🔍 Key Findings</h2>
<ul>
  <li>5,000 unique applicants with a <b>65% admission rate</b> (3,210 admitted)</li>
  <li>India is the top source country — <b>59%</b> of all applicants</li>
  <li><b>2024 Fall</b> was the peak intake period</li>
  <li>Most applied-for programs: <b>Business Analytics</b> &amp; <b>Computer Science</b></li>
  <li>Biggest pipeline bottleneck: <b>Missing Transcripts</b> (1,177 applicants)</li>
  <li>Highest admission rate: <b>Jarvis College of Computing &amp; Digital Media (71%)</b></li>
</ul>

<p>
  📁 <a href="https://drive.google.com/file/d/1uiquQGzrbsg_-sto0q3s15OagCA905Fw/view?usp=drive_link">Cleaned Dataset</a>
  &nbsp;·&nbsp;
  📊 <a href="https://docs.google.com/spreadsheets/d/1cH6kXGclqJZ6VpLtDVJXzY1iDij9r54-/edit?usp=drive_link&ouid=107074866250955083491&rtpof=true&sd=true">Full Documentation</a>
</p>
