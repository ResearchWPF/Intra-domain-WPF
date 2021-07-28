# Include datasets for the Intra-domain WPF 
## This work has been published in The Web Conference 2021
## Each website includes 4 datasets denoted as D1, D2, D3 and D6 <br/>
**D1** includes 1000 pages with 50 traces for each page, collected in **National University of Singapore**. <br/>
**D2** includes 300 pages with 50 traces for each page, collected from **The University of Queensland**<br/>
**D3** includes 300 pages with 50 traces (monitored pages in open-world setting) and up to 30,000 pages with 1 trace each (unmonitored pages). **D3** is collected in **National University of Singapore**. <br/>
**D6** includes 100 pages with 500 traces for each page, collected on servers hosted by AWS located in Singapore. <br/>
For each website, we include raw traffic datasets after anonymization and processed datasets after extracting the CDN bursts (D1, D2 and D3).

The outliers and been removed for each dataset uploaded here.<br/>
For D1, D2 and D3, we have included the full traces and anonymized the IP addresses with the IP mapping enclosed in each dataset for each webpage. <br/>
For D6, we have included the first 3000 packets for each trace. After pre-processing, we keep the size and direction of each packet. A positive size indicates the incoming packet to the user browser from the CDN server; a negative size indicates the outgoing packet from the user to the CDN server. For longer traces (>3000 packets), the subsequent packets are truncated; for shorter traces (<3000 packets), the traces are padded with 0 up to the 3000th packet.
