# 🔆LPRS™ Live Proxy Relay Server

The 🔆<b>LPRS™ Live Proxy Relay Server</b> is a powerful, low-latency media gateway and proxy server engineered to meet the rigorous demands of professional television and broadcast operations, utilizing cutting-edge transport protocols.

🔆<b>LPRS™</b> is built to eliminate the complexity and cost traditionally associated with multi-protocol, high-quality stream distribution.

✅ <b>Protocol Agnostic Native Support</b>: Natively supports all essential modern protocols: <b>SRT</b> / <b>RIST</b> / <b>RTMP</b> / <b>RTMPS</b> / <b>HLS</b> / <b>WebRTC</b> / <b>RTSP</b>. Functions as a true agnostic, real-time, multi-format, multi-standard media relay server, supporting any audio/video/data format WITHOUT requiring proprietary hardware or software modifications to your existing infrastructure.

<img width="3000" height="1760" alt="lprs new generation media distribution" src="https://github.com/user-attachments/assets/fa1e7915-2743-4a91-892b-2927eeef901f" />

✅ <b>Scalable & High-Quality Distribution</b> & <b>Simultaneous Multi-Stream Transport</b>: Capable of transporting multiple independent audio-video streams concurrently. One-to-Many HD/UHD/4K: Efficiently distributes a single HD, UHD, or 4K source stream to 'N' simultaneous receivers.<br>

✅ <b>Zero-Loss Quality Assurance (NO Transcoding)</b>: Achieves transparent multiplication and distribution of the signal to 'N' users at the highest available source quality, entirely eliminating quality degradation associated with transcoding.

🔎Complex Real-Time <b>Accurate & Detailed Health Metrics and Statistics</b> for every streams passed!
The live stream health stats gives a greater insight into the performance of the active live streams on server.

<img width="1486" height="835" alt="LPRS metrics" src="https://github.com/user-attachments/assets/b0ab0cb3-e9db-4e73-85a0-5295d4ee09c5" />

✅ <b>Operational Control & Security</b> & <b>Advanced Stream Management</b>: Provides granular control and monitoring over all received streams and connected users.<br>

✅ <b>Broadcast-Grade Security</b>: Ensures content protection during transport via robust AES Encryption.

<img width="1920" height="1079" alt="lprs 5media player dashboards Zoom" src="https://github.com/user-attachments/assets/134942b5-b0b1-440c-b999-245e5a89ebdc" />

✅ <b>Production Workflow Enhancement</b>: Generalized Acquisition & Exchange: Significantly expands production possibilities by standardizing the reliable acquisition and exchange of live TV productions using ubiquitous SRT/RIST/RTMP/RTMPS/RTSP streams over public internet.<br>

✅ <b>Proven Reliability & Value</b>: Application fully tested and validated in demanding broadcast environments, offering powerful capabilities at an UNBEATABLE cost profile.

<img width="1430" height="811" alt="lprs 4channel monitor" src="https://github.com/user-attachments/assets/96689f2c-1bb7-4717-8450-6621fccce1b6" />

✅ <b>Perfect for Hybrid Satellite-IP workflow</b>: A content distribution strategy that combines the reliability and wide reach of traditional satellite technology with the flexibility, scalability, and interactivity of modern IP-based (Internet and cloud) networks. This approach allows broadcasters to leverage the strengths of both systems to optimize delivery, reduce costs, and meet changing viewer demands.

<img width="1920" height="1080" alt="lprs stability and reliability" src="https://github.com/user-attachments/assets/7a817fa2-439d-417e-9be4-9e5272592a42" />

✅ <b>This system is tuned, optimized, and ready for immediate, high-volume operation</b>. Deploy once and forget the instability—retaining operational simplicity even as your enterprise scales exponentially.<br>

✅ <b>Unrivaled Performance & Resilience</b>: Maximize your operational capacity with a system architected for absolute stability, high availability, and the latest technology standards.<br>

✅ <b>Strategic Simplicity</b>: Experience true "<b>Set It and Forget It!</b>" operational ease. The platform is pre-tuned, fully optimized, and ready for immediate deployment, minimizing maintenance overhead and freeing up key engineering resources.

<img width="1467" height="826" alt="LPRS™ Do The MagiX Zoom" src="https://github.com/user-attachments/assets/3326527c-79df-4ee6-9f0d-eefd2f5faaff" />

✅ <b>Native support</b> for all major/used protocols (SRT/RIST/MPEGTS/RTMP/RTMPS/RTSP/RTP/UDP) and codecs (H264/AVC, H265/HEVC, AV1, VVC etc.) in broadcast and media industry, Ultra Low latency limited only by the characteristics of your equipment and your infrastructure.

✅ <b>NO Quality Loss</b>, Advanced Real-Time Monitoring, Easiest Remote Management model, Low-footprint CPU and Memory usage, Lightweight & Ultra-responsive Runtimes, On-Premise or On-Cloud distribution, Lowest Costs, Advanced Users Management, Extended logging capabilities. In One place!

<img width="1486" height="835" alt="Screenshot 2026-04-04 at 18-07-39 LPRS™ Live Stream Player" src="https://github.com/user-attachments/assets/a4a82709-6f3c-43b7-8b64-95e548deebc4" />

<img width="1471" height="826" alt="Screenshot 2026-03-07 at 21-26-46 LPRS™ Live Stream Player" src="https://github.com/user-attachments/assets/0ca15c40-527c-40d7-aab5-bd441cd36f62" />



# 🚀How to Install/Test It

The install is as simple as possible since 🔆<b>LPRS™ Live Proxy Relay Server</b> is a fully dockerized app:
* Download the <a href="https://github.com/laurfb/LPRS/blob/main/docker-compose.yml">docker-compose.yml</a>
* Copy docker-compose.yml in any folder you want
* Run in that folder (asuming you already have docker engine instaled): <b>docker compose up -d</b>
* Then, access the 🔆<b>LPRS™</b> web interface in any browser you want with <a href="http://localhost:9998">http://localhost:9998</a> address from local or use <a href="http://server_address:9998">http://server_address:9998</a> if you acces the server from other IP


# ✨Project based and inspired by:
* libSRT: https://github.com/Haivision/srt
* libRIST: https://code.videolan.org/rist/librist 
* Enhanced rtmp: https://github.com/veovera/enhanced-rtmp
* Node.js: https://github.com/nodejs 
* Edward Wu's SRT Live Server: https://github.com/Edward-Wu/srt-live-server
* NGINX server: https://nginx.org/
* OSSRS/SRS (Simple Realtime Server): https://github.com/ossrs/srs
* Arut nginx rtmp module: https://github.com/arut/nginx-rtmp-module
* Ravenium docker file: https://github.com/ravenium/srt-live-server
* BtbN ffmpeg LGPL builds: https://github.com/BtbN/FFmpeg-Builds
* Build on Ubuntu 25.x : https://ubuntu.com/ 

🫡All credits goes to the original authors!


