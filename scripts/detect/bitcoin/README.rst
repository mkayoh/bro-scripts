source: https://github.com/jsiwek/bro_bitcoin 

Bro Module for Detecting Cryptocurrency (Bitcoin) Mining Hosts
==============================================================

This script module for Bro can detect Bitcoin, Litecoin, PPCoin, or
other cryptocurrency mining traffic that uses `getwork
<https://en.bitcoin.it/wiki/Getwork>`_, `getblocktemplate
<https://en.bitcoin.it/wiki/Getblocktemplate>`_, or `Stratum
<http://mining.bitcoin.cz/stratum-mining/>`_ mining protocols over TCP
or HTTP.  Note that the module cannot currently detect the Bitcoin P2P
protocol, which is different from the mining protocols.

See mining.bro for more details on how it works.

