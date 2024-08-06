# RFToy+

RFToy+ is a modified version of RFToy which now includes a web-based Backup & Restore feature and allows you to set the RF Code.

The pre-compiled firmware can be found in the Build directory. 
Use the OTA update URL of http://[IP Address]/update

## RF Code Structure:

- **ON Operation:** Represented by the first 6 hexadecimal digits.
- **OFF Operation**: Represented by the next 6 hexadecimal digits.
- **Timing**: Represented by the final 4 hexadecimal digits (recommend 0158).

### Examples:

- `747a1d0d4aa80158`
- `35d1878b4e730158`
- `bfc664d387440158`

## Recommendation:

- For 1527 Learning Code Wireless Remote  Controllers, consider using the hexadecimal timing code of "0158".
- To verify sufficient binary entropy in the ON/OFF code, convert the hexadecimal values to binary for visual inspection.

