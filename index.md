#### Contact Information
* priyankasag10@gmail<!-- -->.com
* Reading, UK
* [Linkedin](https://www.linkedin.com/in/priyanka-sagwekar-aa755a117/)

## Check out my Projects!

### Project 1
<section class="project">
  <h2>Automated Environmental QA/QC &amp; EDD Validation Engine</h2>
  <p class="tech"><em>Python · SQL Server · pandas · Excel reporting · GIS</em></p>

  <p>
    Laboratory data must be checked before it reaches a project database. This is a pipeline
    that automates those checks. It loads lab Electronic Data Deliverables (EDDs) from CSV or
    Excel into a SQL Server staging area. It then runs 36 automated QA/QC rules and writes a
    formatted Excel exception report for each file. Only data that passes is promoted to the
    master database, with standard validation qualifiers attached.
  </p>

  <h3>Key features</h3>
  <ul>
    <li>Checks holding times, blank contamination, surrogate and spike recoveries, field duplicates and detection limits.</li>
    <li>Also checks cooler temperatures, borehole depths, well screens and links to reference data.</li>
    <li>Keeps every limit in database tables, so a data manager can change rules without touching code.</li>
    <li>Uses a data model based on EQuIS, with a stored procedure that promotes clean data in one transaction.</li>
    <li>Produces an import decision for each file: go, partial or no-go.</li>
    <li>Exports each location's QC status in British National Grid coordinates, ready for ArcGIS.</li>
  </ul>

  <h3>Results</h3>
  <ul>
    <li>Tested on six simulated lab files for a fictional UK site, covering groundwater and soil.</li>
    <li>Caught all 53 deliberately injected errors, with zero false alarms on clean data.</li>
    <li>Correctly rejected one badly broken file and partly promoted the other five.</li>
    <li>Covered by 17 automated tests, including an end-to-end SQL Server test.</li>
  </ul>

  <p>Exception Report Summary Sheet after QA/QC Checks</p>
  <img src="Images/QA-QC-Report-Summary.png" alt="Exception Report Summary Sheet after QA/QC Checks" width="500" height="300">
  <p><a href="https://github.com/PriyankaSagwekar/EDD-Validation-Engine-and-QA-QC">View the code on GitHub</a></p>
</section>

### Project 2
**Interactive AGS 4 Borehole & Groundwater Log Profiler**
<br> **Target Skills:** AGS Data Formats, Contaminated Land/Hydrogeology context, Python (python-ags4), Streamlit/Dash
<br> **The Concept:** Build a lightweight web application that allows ground engineers to upload a raw .ags file and instantly see structured data groups and borehole stratigraphy.

### Project 3
**Automated Contaminated Land GIS & Screen-Limit Dashboard**
<br> **Target Skills:** GIS/Spatial Visualization, Regulatory Screening, Dashboarding
<br> **The Concept:** An automated dashboard that flags statutory environmental guideline exceedances (e.g., UK Soil Guideline Values or EA Groundwater protection targets) and maps them spatially.

### Project 4
**ArcGIS Geoprocessing of Technical data**
<br> **Target Skills:** Python, AGS4 file processing, ArcGIS, Geotechnical data understanding
<br> **The Concept:** Synthetic AGS4 dataset modeling a benzene leak scenario across five monitoring locations at the refinery. 3D cross-sections and subsurface soil profiles in ArcGIS Pro using this AGS data

## Certifications
[Fundamentals of ArcGIS](https://coursera.org/share/e6d48ea8088d4a94b603c41b0cadcfb8) by University of California, Davis on Coursera <br><br>
<i>As part of the course practicals, I developed and exported a map of the river and watershed systems in the Navarro region of California, USA. Throughout this project, I explored a wide range of cartographic features and ArcGIS tools. Specifically, I gained hands-on experience in connecting databases and data sources, creating multi-layered maps, utilizing basemaps, and applying advanced symbology and labeling. I also incorporated essential map elements such as north arrows, map scales, metadata, and dynamic text, while learning how to generate automated map series. Furthermore, I utilized core geoprocessing tools—including proximity and buffer analyses—and managed spatial data through table joins, spatial joins, and relates. This analytical workflow was highly rewarding, and I thoroughly enjoyed bringing the data to life.</i><br><br>
<img src="Images/Navarro_River_Systems.jpg" alt="Snapshot of map developed in ArcGIS" width="500" height="400">
<br><br>
<i>More interestingly as a part of final project for the course, I worked on GIS analysis of wildfires impact in California. Please check out my map package [here](https://ucd-cpe.maps.arcgis.com/home/item.html?id=771eb48128f64f5b945c08ca292a3242#overview)</i>
<br>
<img src="Images/Wildfire_Impact_California.jpg" alt="Snapshot of map developed in ArcGIS" width="400" height="475">
<br><br>
Specialisation in GIS (including 3 other courses) is in Progress.
