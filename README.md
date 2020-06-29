# BVT_MQTT_client

Beyless Vending Terminal, Python MQTT client

## user example
conn = mqtt_connector('192.168.10.19', 1883, 20001) #create mqtt connector object
conn.collect_dataset('20001', 1) #get grame
print(conn.get_result()) #print image id
