# Radio Docker image build

## setup

```
echo '# disable DVB drivers
blacklist rtl2830
blacklist rtl2832
blacklist dvb_usb_rtl28xxu' > /etc/modprobe.d/rtlsdr.conf
```
