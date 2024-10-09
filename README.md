# match_origin_as_fallback bug

## Steps

1. Install the unpacked extension from `ext/` into Chrome
2. Open `test.html`
3. Click the `Click me` button.
4. Observe that a window pops open and then immediately closes.
5. Expected behavior is that a print dialog should be shown first.
