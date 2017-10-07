### I just try to reborn stratum to work with all need algos.
### Need contributors!

#### Hashing algorithms supported:
* ✓ __SHA256__ (tested with VCOIN)
* ✓ __Scrypt__ (tested with AntiLiteCoin, 1CREDIT, ArgusCoin, WAYAWOLFCOIN and many others)
* (-) __Scrypt-Jane__ (submitblock not working tested with CacheCoin, Yacoin)
* ? __Scrypt-N__ (need tests)
* ? __Quark__ (need tests)
* ✓ __X11__ (tested with BrainCoin, CannabisCoin, AdzCoin and many others)
* ? __X11Ghost__ (need tests)
* ✓ __Groestl__ (tested only shares with AuroraCoin, blocks not tested)
* ? __X13__ (need tests)
* ? __Lyra2Z__ (need tests)
* ? __NIST5__ (need tests)
* ? __Keccak__ (need tests)
* ? __Skein__ (need tests)
* ? __Blake__ (need tests)
* ? __Fugue__ (need tests)
* ? __Qubit__ (Shares works, blocks finding, but error 'We thought a block was found but it was rejected by the daemon'. No blocks presented in pools web interface)
* ? __SHAvite-3__ (need tests)
* ? __Sha1__ (need tests)
* ? __Hefty1__ (need tests)
* ? __Cryptonight__ (need tests)

### Requirements
------------
* Node 8.x.x
* coin daemon

### License
-------
Released under the GNU General Public License v2
http://www.gnu.org/licenses/gpl-2.0.html

### Credits
-------
* [Jerry Brady / mintyfresh68](https://github.com/bluecircle) - got coin-switching fully working and developed proxy-per-algo feature
* [Tony Dobbs](http://anthonydobbs.com) - designs for front-end and created the NOMP logo
* [LucasJones](//github.com/LucasJones) - got p2p block notify working and implemented additional hashing algos
* [vekexasia](//github.com/vekexasia) - co-developer & great tester
* [TheSeven](//github.com/TheSeven) - answering an absurd amount of my questions and being a very helpful gentleman
* [UdjinM6](//github.com/UdjinM6) - helped implement fee withdrawal in payment processing
* [Alex Petrov / sysmanalex](https://github.com/sysmanalex) - contributed the pure C block notify script
* [svirusxxx](//github.com/svirusxxx) - sponsored development of MPOS mode
* [icecube45](//github.com/icecube45) - helping out with the repo wiki
* [Fcases](//github.com/Fcases) - ordered me a pizza <3
* Those that contributed to [node-stratum-pool](//github.com/zone117x/node-stratum-pool#credits)