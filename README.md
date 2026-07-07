# Memcoin Wallet

Browser-based tools for interacting with a Memcoin node. Each is a single self-contained HTML file — no build step, no external dependencies, no network calls beyond your own node's RPC endpoint.

## Files

| File | Purpose |
|---|---|
| `memcoin_interface.html` | Wallet — addresses, balances, sending |
| `memcoin_explorer.html` | Block and mempool explorer |
| `payment_monitor.html` | Watch incoming TX1 payments to an address |
| `network_monitor.html` | Node and network status |
| `memcoin_memory_player.html` | Encode/decode the nonce field as text or music |

## Requirements

- A running Memcoin node reachable via JSON-RPC, with its wallet loaded
- A modern browser

## Usage

Open any file directly in a browser, or serve the directory with any static file server. Each page connects to the node's RPC endpoint (default `http://localhost:9332`) using the credentials configured in that page.

## License

MIT — see [LICENSE](LICENSE).
