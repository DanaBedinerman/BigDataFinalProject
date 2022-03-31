Steps to flow before execution:

1.	Install the following packages:
	a.	Schedule
	b.	PyArrow
	c.	confluent-kafka
	
2.	Make sure the config file is in the execution folder, and the file has the following structure:
	a.	List of the desired topics from Wikipedia
	b.	Start date in the format yyyymmdd
	c.	End date in the format yyyymmdd
	d.	Prediction date in the format yyyymmdd
	e.	The threshold for anomaly
	
3.	The used topic for Kafka is ‘wiki’
