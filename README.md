BlueskyClientAPIcall_ELF64bit_x86_64
====================================
 Here is a client API caller(Demo version 1) of Blue-sky server binary execution for x86_64 machines. You can clone it and copy to executionable directory. 

 **For example (Linux):**

  ```shell 
   $> sudo cp SKYBLUECLIENT /usr/bin/.

   $> edIP="Your RaspberryPI IP address."

   $> GPIO_PIN_NUMBER_OF_YOUR_DEFINE="3"

   $> BLUESKYSERVER="127.0.0.1:8189"

   $> SKYBLUECLIENT -c "http://${BLUESKYSERVER}" -s "sensornetwork ${edIP} set d ${GPIO_PIN_NUMBER_OF_YOUR_DEFINE} 1"

   $> SKYBLUECLIENT -c "http://${BLUESKYSERVER}" -s "sensornetwork ${edIP} get d ${GPIO_PIN_NUMBER_OF_YOUR_DEFINE}"

   $> SKYBLUECLIENT -c "http://${BLUESKYSERVER}" -s "sensornetwork ${edIP} set d ${GPIO_PIN_NUMBER_OF_YOUR_DEFINE} 0"
  
  ```
