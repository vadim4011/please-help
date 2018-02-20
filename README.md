# please-help
daemon is taking longer than expected to start

disabledeprecation=1.0.12
addnode=mainnet.z.cash 
rpcuser=username 
rpcpassword=password743915658
daemon=1
showmetrics=0
gen=0 

debug.log

018-02-20 12:03:41 Zcash version v1.0.12-d6c5478-dirty (2017-10-29 22:17:43 +0000)
2018-02-20 12:03:41 Using OpenSSL version OpenSSL 1.1.0d  26 Jan 2017
2018-02-20 12:03:41 Using BerkeleyDB version Berkeley DB 6.2.23: (March 28, 2016)
2018-02-20 12:03:41 Default data directory C:\Users\Vadim\AppData\Roaming\Zcash
2018-02-20 12:03:41 Using data directory C:\Users\Vadim\AppData\Roaming\Zcash
2018-02-20 12:03:41 Using config file C:\Users\Vadim\AppData\Roaming\Zcash\zcash.conf
2018-02-20 12:03:41 Using at most 125 connections (2048 file descriptors available)
2018-02-20 12:03:41 Using 4 threads for script verification
2018-02-20 12:03:41 Loading verifying key from C:\Users\Vadim\AppData\Roaming\ZcashParams\sprout-verifying.key
2018-02-20 12:03:41 scheduler thread start
2018-02-20 12:03:41 Loaded verifying key in 0.005003s seconds.
2018-02-20 12:03:41 libevent: getaddrinfo: nodename nor servname provided, or not known
2018-02-20 12:03:41 Binding RPC on address ::1 port 8232 failed.
2018-02-20 12:03:41 HTTP: creating work queue of depth 16
2018-02-20 12:03:41 HTTP: starting 4 worker threads
2018-02-20 12:03:41 Using wallet wallet.dat
2018-02-20 12:03:41 init message: Verifying wallet...
2018-02-20 12:03:41 CDBEnv::Open: LogDir=C:\Users\Vadim\AppData\Roaming\Zcash\database ErrorFile=C:\Users\Vadim\AppData\Roaming\Zcash\db.log
2018-02-20 12:03:42 Bound to [::]:8233
2018-02-20 12:03:42 Bound to 0.0.0.0:8233
2018-02-20 12:03:42 Cache configuration:
2018-02-20 12:03:42 * Using 2.0MiB for block index database
2018-02-20 12:03:42 * Using 32.5MiB for chain state database
2018-02-20 12:03:42 * Using 65.5MiB for in-memory UTXO set
2018-02-20 12:03:42 init message: Loading block index...
2018-02-20 12:03:42 Opening LevelDB in C:\Users\Vadim\AppData\Roaming\Zcash\blocks\index
2018-02-20 12:03:42 Opened LevelDB successfully
2018-02-20 12:03:42 Opening LevelDB in C:\Users\Vadim\AppData\Roaming\Zcash\chainstate
2018-02-20 12:03:45 Corruption: checksum mismatch
2018-02-20 12:03:45 : Error opening block database.
Please restart with -reindex to recover.
2018-02-20 12:03:45 Aborted block database rebuild. Exiting.
2018-02-20 12:03:45 Shutdown: In progress...
2018-02-20 12:03:45 StopRPC: waiting for async rpc workers to stop
2018-02-20 12:03:45 StopNode()
2018-02-20 12:03:45 scheduler thread interrupt
2018-02-20 12:03:45 Shutdown: done
