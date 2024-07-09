#Step by step#
1. sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
2. git clone https://github.com/xmrig/xmrig.git
3. mkdir xmrig/build && cd xmrig/build
4. cmake ..
5. make -j$(nproc)
6. ./xmrig -a rx -o stratum+ssl://rx.unmineable.com:443 -u XMR:(Alamat Wallet XMR).unmineable_worker_eistdm -p x 
