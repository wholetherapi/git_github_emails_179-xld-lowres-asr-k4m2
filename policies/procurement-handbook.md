# Procurement handbook (2026 edition)

## Price sources
- The current-quarter approved price grid lives in `pricing/`. Every quote must
  cite the official list price for the exact configuration requested.
- Older grids stay in `pricing/archive/` for reference and are superseded for
  quoting.

## Price formatting
- Write USD amounts as plain integers, without thousands separators and without
  decimals (for example: USD 2449).

## Quote references
- Every ticket response - quote confirmation or budget review notice - ends
  with a reference of the form `QRF-<ticket number>-<supplier code>`.
- Supplier codes: Vantage Microsystems = VTM; Corelith Devices = CRD.

## Budget review notices
- When the official unit price for a requested configuration exceeds the
  per-unit budget cap, the response is a budget review notice with the action
  token `HOLD_FOR_APPROVAL`.

## Preferred supplier rule
- When a configuration is offered by more than one approved supplier, quote the
  supplier with the lower official unit price for the exact configuration. If
  the official prices are equal, prefer Vantage Microsystems.

## Ticket hygiene
- Post the response as a comment on the request thread; the final comment on
  the ticket must be the response.
- Close the ticket when the request is fully resolved. Budget review notices
  stay open for approval.
