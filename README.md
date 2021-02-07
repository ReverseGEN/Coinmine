# Coinmine
Coinmine


Usage: CoinmineXMR [OPTION]...

  -h, --help                 show this help
  -v, --version              show version number
  -V, --version-long         show long version number
  -c, --config FILE          common miner configuration file
  -C, --poolconf FILE        pool configuration file
  --noTest                   disable the startup POW self test
  --benchmark BLOCKVERSION   ONLY do a benchmark and exit
  --benchwait WAIT_SEC             ... benchmark wait time
  --benchwork WORK_SEC             ... benchmark work time
  --noCPU                    disable the CPU miner backend
  --cpu FILE                 CPU backend miner config file
  --log FILE                 miner output file
  --h-print-time SEC         interval for printing hashrate, in seconds
  -i --httpd HTTP_PORT       HTTP interface port

The following options can be used for automatic start without a guided config,
If config exists then this pool will be top priority.
  -o, --url URL              pool url and port, e.g. pool.usxmrpool.com:3333
  -O, --tls-url URL          TLS pool url and port, e.g. pool.usxmrpool.com:10443
  -u, --user USERNAME        pool user name or wallet address
  -r, --rigid RIGID          rig identifier for pool-side statistics (needs pool support)
  -p, --pass PASSWD          pool password, in the most cases x or empty ""
  --use-nicehash             the pool should run in nicehash mode
  --currency NAME            currency to mine
  --noDevSupport             To improve our support the miner is sending information
                             to the development server.
                             Use this option to disable sending system information.
                             data send:
                                 miner version, used algorithm, system hardware overview
                                 and number of used threads.

Supported coin options:
        - arqma
        - keva
        - loki
        - monero
        - safex
        - randomx
        - randomx_arqma
        - randomx_keva
        - randomx_loki
        - randomx_safex
        - randomx_wow
        - wownero

