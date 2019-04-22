# AggreGate-server-demo
This simple application shows you how to store or monitor a variable in AggreGate. 

This app has only one variable "DR", a temperature reading. When the temperature reading is received it is stored in the settings file. This is done in on_ser_data_arrival()

Aggregate reads the settings libaray and the value is showm in the AggreGate server.
