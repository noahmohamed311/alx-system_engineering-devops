![500](https://user-images.githubusercontent.com/69303159/201354808-b29d8447-fe10-41f2-9b63-84e759139529.jpg)

<h1>BooktifuL requests a failure report</h1>

<p>Last week, it was reported that the BooktifuL platform was returning 500 Error on all requests made via platform routes, and that all services were unavailable. 90% of users were impacted. The failure of our master server web-01 was the root cause.<p/>

<h2>  Timeline </h2>

<p>When our Site Reliability Engineer, Mr. Emobile, saw the master server lagging in performance on Tuesday, November 8th at 12:00 hours (East Africa Time), he discovered the fault. Our on-call engineers unplugged the master server web-01 for additional system examination and routed all queries to client-server web-02. They resolved the issue by Friday, November 11th, 22:00 hours (East Africa Time).</p>
 # 12:00 AM - Server error occurs and outage is detected
 # 12:02 AM - On-call devOps team checks the error logs
 # 12:03 AM - Updates error configuration
