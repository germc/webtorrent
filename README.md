webtorrent - BitTorrent over WebRTC
==========

A streaming torrent client in your browser, powered by webRTC and black magic.

![Magic](https://raw.github.com/feross/webtorrent/master/logo.png)

**Watch / star repo to follow along with progress**

## Features

- **BitTorrent in your browser!**
- **No plugins** (uses WebRTC Data Channels for peer-to-peer data)
- **Streaming playback** (get first pieces first)
  - Into `video` tag with MediaSource API when possible
  - Flash player with JS bridge for other media types
- Works with .torrent files and magnet links
- Supports DHT (trackerless torrents) over WebRTC
  - Extensions to DHT protocol to work over WebRTC
  - DHT nodes do "peer introductions" so WebRTC can work without a centralized signaling server
- **Supports completely serverless, trackerless operation**

## Useful Links

- [BitTorrent Spec](https://wiki.theory.org/BitTorrentSpecification)

### DHT

- [DHT Protocol](http://www.bittorrent.org/beps/bep_0005.html)
- [Kademlia Paper](http://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)
- [Main DHT implementation](https://github.com/jech/dht)
- [Optimized DHT bootstrap implementation](https://github.com/jech/dht-bootstrap)
