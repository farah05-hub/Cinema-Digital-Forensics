 CINEMA FORENSICS EVIDENCE PACK

All evidence is fictional and created for academic practice. No real people, cinemas, payment cards, accounts, or systems are involved.

Primary Tool: Splunk Enterprise

Suggested analysis:
1. Import the extracted evidence files into Splunk.
2. Use the `main` index to search and analyze the evidence.
3. Examine the reservation records for booking IDs BK-2101 through BK-2108.
4. Correlate the booking records with device ID DEV-77A and IP address 198.51.100.24.
5. Examine payment outcomes (DECLINED and TIMEOUT) and compare them with BK-2109 and TX-9009, the successful control booking.
6. Review the web access and seat status records to identify related activity.
7. Record findings with screenshots. Do not claim that a shared IP address or device proves a specific person's identity.

Preservation:
- Keep the ZIP file and extracted original folder unchanged.
- Use a separate working copy for analysis.
- Calculate SHA-256 hashes for the original evidence files before and after transfer and compare them with `08_hashes_sha256.txt`.
- The hash manifest does not hash itself.

IP addresses use documentation-only ranges (198.51.100.0/24 and 203.0.113.0/24). Emails use example.com. All names and phone numbers are fictional placeholders.