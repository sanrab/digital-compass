# digital-compass
digital compass with raspberry, IMU 9255 and tinypilot


sensor IMU 9255 10 DOF
sensor --> GPIO
SDA --> SDA
SCL --> SCL
GND --> GND
VCC --> 3.3V

tinypilot (https://pypilot.org/)

RaspberryPi ZeroW (or Raspberry Mod.B+ with ASUS USB-N13 wifi dongle)

crea Access Point SSID pypilot (senza password)
con IP 192.168.14.1
su TCP porta 20220 dati NMEA roll, pitch, heading + eventuali altri dati NMEA (per es. GPS UBLOX 7)
letti da opencpn (TCP, porta 20220)

con browser su 192.168.14.1:80 calibrazione IMU 9255

oppure:
tinypilot si attacca alla rete openplotter con IP 10.10.10.69
