# Real-Time-Public-Transport-Data-Analytics-Dashboard-Adelaide-Metro
Live public transport analytics dashboard using Python (Colab) and Power BI.

**Data Source (API)** : Used the Adelaide Metro GTFS Realtime API to fetch live transport data (trip updates, positions, routes). (Data Acquisition)

**Python Processing** : Parsed binary Protobuf data, merged trip + vehicle updates, served as JSON via Flask API. (Data Engineering / ETL) 

**Power BI Integration** : Connected Power BI to a live JSON endpoint (via ngrok) and visualized real-time location data. (Data Visualization)   

**Dynamic Dashboard** : Built a live, interactive map that updates as new data arrives. (BI / Reporting)       

**Streaming Concept** : Demonstrates near real-time analytics workflow, similar to modern data streaming solutions. (Real-Time Data)
