# hw1
1. 
    (a) 2Mbps>1Mbps>500Kbps, throughput = 500Kbps\
    (b) 1Mbps>500Kbps>200Kbps, throughput = 200Kbps
2. 
    (a) 2Mbps/100Kbps = 20 people\
    (b) 20%\
    (c) $$ {40 \choose n} * {0.2}^{n}* {(1-0.8)}^{40-n}$$
    (d) $$ \sum\limits_{i=21}^{40} ({40 \choose i} * {0.2}^{i}* {(1-0.8)}^{40-i})$$
3. $$ \frac { (\sum\limits_{i=0}^{N-1} (i)) L}{RN} $$
    $$= \frac{\frac{(N-1)}{2}*N *L}{RN}$$
    $$= \frac{(N-1)*L}{2R}$$
4. * $$\frac{L}{R_1}+\frac{d_1}{s_1} +\frac{L}{R_2}+\frac{d_2}{s_2}$$
   * $$\frac{1000byte}{2Mbps}+\frac{4000km}{2*10^8 m/s} +1msec+ \frac{1000byte}{2Mbps}+\frac{1000km}{2*10^8 m/s}$$
    $$ = (\frac{1000*8}{2000000 }*2)s+\frac{ (4000+1000)*1000}{2*10^8}s+1msec$$
    $$ =  0.033s +1msec = 0.034s $$
5. 
    * Physical Layer
        * rincipal responsibilities: bits “on the wire”
    * Data-Link Layer
        * rincipal responsibilities: data transfer between neighboring network elements
    * Network Layer
        * rincipal responsibilities: routing of datagrams from source to destination
    * Transport Layer
        * rincipal responsibilities: process-process data transfer
    * Application Layer
        * rincipal responsibilities: supporting network applications