# Available-Open-Data and CDS Toolbox

<P>Below are listed some selected Open Climate data and services from both the Copernicus Climate Change Service (C3S) and the Copernicus Atmosphere Monitoring Service (CAMS) which #OpenDataHack2018 participants may find most useful. Data Samples are also provided.

<blockquote><u><strong>Good-to-Know: What is the difference between Analysis, Forecast and Reanalysis?</strong></u>
<br><p>
  An <strong>analysis</strong>, of the atmospheric conditions, is a blend of observations with a previous forecast. An analysis can only provide instantaneous parameters.
<P>
  A <strong>forecast</strong> starts with an analysis at a specific time (the 'initialization time'), and a model computes the atmospheric conditions for many 'forecast steps', at increasing 'validity times', into the future. A forecast can provide instantaneous parameters (e.g. the temperature at the validity times), accumulated parameters (e.g. precipitation in a certain period up to the validity times) and min/max parameters (e.g. min/max of 2 metre temperature in a certain period up to the validity times).
<p>
A <strong>reanalysis</strong> gives a numerical description of the recent climate, produced by combining models with observations. A reanalysis typically extends over several decades or longer, and covers the entire globe from the Earth’s surface to well above the stratosphere. Reanalysis products are used extensively in climate research and services, including for monitoring and comparing current climate conditions with those of the past, identifying the causes of climate variations and change, and preparing climate predictions.   
</blockquote>
  
<hr>

<h3>C3S ERA5 - Global Climate Reanalysis data (2008-present available now)</h3>
<ul>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/What+is+ERA5">What is ERA5</a>
<li><a href="https://software.ecmwf.int/wiki/display/CKB/ERA5+data+documentation">ERA5 documentation</a>
<li>Download ERA5 data via the <a href="https://cds.climate.copernicus.eu/#!/home">Climate Data Store</a>
<li>ERA5 data samples available <a href="https://github.com/OpenDataHack2018/Available-Open-Data/tree/master/C3S/ERA5">HERE</a> in csv format along with <a href="https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/README_ERA5_sample.txt">README file</a>.  Plotting scripts also available <a href="https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/ERA5_monthly_mean_data.ipynb">HERE</a>.
</ul>

<h3>C3S Data from the Sectoral Information System (SIS) for the WATER, ENERGY and INSURANCE sectors</h3>
<ul>
<li><a href="http://edge.climate.copernicus.eu">End-to-end Demonstrator for improved decision making in the water sector in Europe (EDgE)</a>: EDgE is producing a climate information system <a href"http://edge.climate.copernicus.eu/Tools/">"Map Viewer"</a> to allow end-users to find, understand and access the range of climatological and hydrological data and indicators. 

<li><a href="http://swicca.eu/">Service for Water Indicators in Climate Change Adaption (SWICCA)</a> offers readily available <a href="http://swicca.eu/climate-impacts-maps/">climate-impact data, graphs and maps</a> to speed up the workflow in climate-change adaptation of water management across Europe.  

<li><a href="http://ecem.climate.copernicus.eu/">European Climatic Energy Mixes (ECEM)</a> is developing a <a href="http://ecem.climate.copernicus.eu/demonstrator/">Demonstrator</a> to enable the energy industry and policy makers to assess how well energy supply will meet demand in Europe over different time horizons, focusing on the role climate has on energy supply and demand.

<li><a href="http://clim4energy.climate.copernicus.eu/">CLIM4ENERGY</a> provides climate change indicators tailored for the energy sector. The <a href="http://c4e-visu.ipsl.upmc.fr/">Clim4energy visualization portal</a> is online, in beta-test. 

<li><a href="">Wind Storm Information Service (WISC)</a> provides historic storm data over Europe from 1940 onwards through the <a href="https://wisc.climate.copernicus.eu/wisc/#/explore">WISC Portal</a>.
</ul>

<h3>C3S Monthly State of Climate (Maps):</h3>
<ul>
  <li>Average surface air temperature monthly maps:
        <ul>
          <li><a href="https://climate.copernicus.eu/resources/data-analysis/average-surface-air-temperature-analysis">Latest monthly map</a>
    <li><a href="https://climate.copernicus.eu/resources/data-analysis/average-surface-air-temperature-analysis/monthly-maps/">Archived maps from August 2015.</a>
      </ul>
    <li>Monthly sea-ice maps:
        <ul><li><a href="https://climate.copernicus.eu/products/monthly-sea-ice-maps">Latest Monthly Maps</a>
        <li><a href="https://climate.copernicus.eu/sea-ice-monthly-maps">Archived maps from March 2017.</a>
      </ul>
    <li>Monthly summaries of precipitation, relative humidity and soil moisture:
        <ul><li><a href="https://climate.copernicus.eu/monthly-summaries-precipitation-relative-humidity-and-soil-moisture">Latest Monthly Maps</a>
        <li><a href="https://climate.copernicus.eu/precipitation-relative-humidity-and-soil-moisture-monthly-maps">Archived maps from April 2017</a>
          </ul>
 </ul>       

<h3>Some C3S Essential Climate Variables (ECVs) available through the <a href="https://cds.climate.copernicus.eu/#!/home">Climate Data Store</a></h3>

<a name="CAMS"></a>

<h3>CAMS Regional Air Quality data including Pollens (European domain, 25W/50E/30N/70N):</h3>
<ul>
  <li>All CAMS regional analysis and forecast daily data (<a href="http://www.regional.atmosphere.copernicus.eu/index.php?category=data_access&subensemble=archived_products">archived since 10/2015</a> and <a href="http://www.regional.atmosphere.copernicus.eu/index.php?category=data_access&subensemble=macc_products">less than 30 days old data</a>, approximately 10km horizontal resolution from surface up to 5000m) 
  <li>CAMS regional reanalyses data also available <a href="http://www.regional.atmosphere.copernicus.eu/index.php?category=data_access&subensemble=reanalysis_products">online</a>. 
  <li><strong>CAMS regional ensemble data sample</strong> at 3000 European locations available <a href="https://github.com/OpenDataHack2018/Available-Open-Data/blob/master/CAMS-regional-air-quality.md">here</a>.
    </ul>
    
<h3>CAMS Global Air Quality data: analysis, forecast and reanalysis</h3>

<ul>
  
<li>CAMS <strong>Global archived analysis and forecast daily data </strong> (6 hourly analysis and 3 hourly up-to 5 days forecast data since 05/07/2012, available with a 5-day delay, approximately 40km horizontal resolution (T511 spectral) on 60 vertical levels from the surface up to 0.1 hPa. Full catalogue of species available <A href="https://atmosphere.copernicus.eu/catalogue#/">HERE</a>
      
<li>CAMS <strong>Global archived reanalysis data</strong> (MACC Reanalysis - 2003-2012, approximately 80 km (T255 spectral) on 60 vertical levels from the surface up to 0.1 hPa for the analysed species). Get sample data files <a href="http://apps.ecmwf.int/datasets/data/macc-reanalysis/levtype=sfc/">HERE</a> (netCDF or GRIB format)
       
  
</ul>


<h3>CAMS Solar and UV Radiation data:</h3>    
<ul>     
  <li>Solar radiation (2004 - present with up to 2 days delay) - global clear-sky solar irradiance and Meteosat satellite field-of-view coverage total-sky surface solar irradiation. This is a time series service, i.e., for one location per request only. Register to download data <a href="http://www.soda-pro.com/web-services/radiation/cams-radiation-service">HERE</a>.
  <li><a href="http://www.soda-pro.com/help/cams-services/cams-radiation-service/download-europe-volume">Solar radiation data and maps for over Europe (2005-2017) </a>
    <li><a href="http://www.soda-pro.com/help/cams-services/cams-radiation-service/download-africa-volume#jade-maps">Solar radiation data and maps for over Africa (2005-2017)</a> 
</ul>

<h3>CAMS Global Fire Monitoring data</h3>
    <ul>
    <li>GFAS (Global Fire Assimilation System) - Get a data sample using the ECMWF data server web interface:http://apps.ecmwf.int/datasets/data/cams-gfas/ - Documentation available <a href="https://software.ecmwf.int/wiki/display/CKB/CAMS++Global+Fire+Assimilation+System+%28GFAS%29+data+documentation">HERE</a>.
    </ul>
    
<h3>CAMS Forecast and Analysis Maps</h3>

<ul>
  <li><a href="http://atmosphere.copernicus.eu/charts/cams_monitoring/">CAMS Monitoring Plots</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/nrt/nrt_fields/">Near-real-time Analysis and Forecast of reactive gases (C-IFS)</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/nrt/nrt_uvindex">Forecast of UV Radiation</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/nrt/fire_radiative_power/">Fire Radiative Power (archive)</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/nrt/nrt_fields_ghg/">GHG forecasts</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/nrt/nrt_opticaldepth/">Forecast of Aerosols Optical Depth</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/reanalysis/macc/macc_monthly_fields/">MACC Reanalysis Monthly Mean fields</a>
  <li><a href="http://macc.copernicus-atmosphere.eu/d/services/gac/reanalysis/macc/macc_monthly_totalcolumns/">MACC Reanalysis Monthly Mean Total Columns</a>
</ul>

<h3>Other Services - CDS Toolbox</h3>
<P>What is the CDS Toolbox?
  <P>The toolbox is a catalogue of software tools that can be classified as:
<ul>
  <li><em>Tools</em> that perform basic operations on data, such as computation of statistics, sub-setting, averaging, value at points, etc
  <li><em>Workflows</em> that combine the output of tools and feed this as input into other tools to produce derived results
  <li><em>Applications</em> which are interactive web pages that allow users to interrogate the CDS through parameterisation; applications make use of workflows and selected data and products in the CDS.
</ul>
<p>The Toolbox is used to create web-based applications that draw on the datasets available in the CDS.
<p>More detailed information about the Toolbox and the CDS in general is available from this <a href="https://www.ecmwf.int/en/newsletter/151/meteorology/climate-service-develops-user-friendly-data-store">ECMWF Newsletter article</a>.
<P>Access the CDS Toolbox <a href="https://cds.climate.copernicus.eu/user/login?destination=/gaia-toolbox">HERE</a> (login account required)
 
<h3>Other Services - ECMWF WMS</h3>
<P>The WMS service operated by ECMWF is part of the ecCharts services to provide forecast weather maps to its users. The service is based on an in-house developed Python package translating WMS requests into the internal request to generate maps which is based on the Magics/Metview parameter language. Currently the serviceprovides WMS version 1.1.1 and 1.3.1. Access is controlled through tokens which are restricted to ranges of IP addresses. The token “public” contains, besides selected weather forecast maps and maps from the Copernicus Atmosphere Monitoring Service (CAMS).</P>

  

<HR>
<P>For all CAMS products, please check <a href="https://software.ecmwf.int/wiki/pages/viewpage.action?pageId=56659592">What data and charts are available through CAMS (Copernicus Atmosphere Monitoring Service)?</a>
<P>For all C3S products, please check <a href="https://software.ecmwf.int/wiki/pages/viewpage.action?pageId=88257857">What data and maps are available through C3S (Copernicus Climate Change Service)?</a>
<P>For access to other ECMWF Open Data products, please go <a href="http://apps.ecmwf.int/datasets/">here</a>.
