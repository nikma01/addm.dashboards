# addm.dashboards & reports
BMC Atrium Discovery and Dependency Mapping

Note:
1) This has been structured for the 8.3 release initialy.  
  The file '10DeployReports_83.xm'l IS VERSION SPECIFIC and you are going to have to 
  keep this up to date when the product is upgraded.
3) The *Reports.xml report files need to go in ~tideway/data/custom/reports on the appliance
4) The *.dash file needs to go in ~tideway/etc/dashboards on the appliance
5) The additional_links.xml file needs to go in ~tideway/data/custom/reports

How to run a Chart direct from an URL:
http://localhost/ui/RunReport?_tw_chart_name=DataCentreStand.Reports.HostByVendorPie
http://localhost/ui/RunReport?_tw_report_name=Resiliency.Report.UnixKernelDist
