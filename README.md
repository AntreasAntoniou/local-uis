# Local UIs

An agent skill and zero-dependency Python launcher for locally running web interfaces.

```bash
npx skills add AntreasAntoniou/local-uis
python3 scan_uis.py --no-open
```

The scanner uses `lsof`, probes loopback over HTTP, and writes a private local dashboard. It does not scan remote hosts.

## Test

```bash
python3 -m unittest discover -s tests
```

MIT licensed.
