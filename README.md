# Network-Project-Amirali-Asadbegi
# پروژه درس گرافیک کامپیوتری  
## نمایش گرافیکی و انیمیشن حرکت پکت‌ها (Ping + DHCP)

دانشجو: امیرعلی اسدبگی  
درس: گرافیک کامپیوتری  

### توضیح پروژه
یک شبکه محلی طراحی شده که هدف اصلیش نمایش بصری و انیمیشنی حرکت پکت‌ها در شبکه است:  
- حرکت پکت‌های ICMP هنگام پینگ  
- فرآیند کامل DHCP (Discover → Offer → Request → ACK) با انیمیشن واقعی  
- استفاده از Simulation Mode برای مشاهده گام‌به‌گام و رنگی پکت‌ها

### توپولوژی شبکه
![توپولوژی پروژه](Packet-Tracer-Lab-XYZ/topology.png)


### فایل‌های پروژه
- Packet-Tracer-Lab-XYZ/ → فولدر اصلی پروژه (همه چیز داخلشه)
- Packet-Tracer-Lab-XYZ/final.pkt → فایل اصلی قابل اجرا
- Packet-Tracer-Lab-XYZ/topology.png → عکس باکیفیت توپولوژی

### نحوه اجرا و دیدن انیمیشن
1. Cisco Packet Tracer (نسخه ۷.۳ یا بالاتر) را باز کنید  
2. فایل زیر را باز کنید:  
   Packet-Tracer-Lab-XYZ/final.pkt  
3. از پایین صفحه به Simulation Mode بروید (آیکون ساعت)  
4. در Event List فیلترها را تنظیم کنید:
   - برای پینگ → فقط ICMP
   - برای DHCP → DHCP + UDP
5. روی Play یا Auto Capture/Play کلیک کنید  
   → انیمیشن حرکت پکت‌ها شروع می‌شه!

 
امیرعلی اسدبگی
