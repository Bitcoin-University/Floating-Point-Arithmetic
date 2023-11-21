https://www.ofnumbers.com/2018/10/01/interview-with-ray-dillinger/

Quote:
>Clearly I hadn’t been the first pessimistic screaming hair-triggered paranoid aware of those issues to go over that accounting code; I could not find a single methods error.  The ‘satoshi’ unit which is the smallest unit of accounting, is selected right above the bit precision that can be handled with NO rounding in the double float format, and every last operation as far as I could find was implemented in ways that admit no rounding of any bits that would affect a unit as large as a satoshi.
>
>To cause rounding of satoshis in the Bitcoin code, someone would have to be adding or subtracting more than 21 million Bitcoins (I think it’s actually 26 million, in fact…).  So, the Bitcoin chain is, I believe, rounding-free and will continue to check regardless of whether clients use any higher floating point precision.

# Top.Crucial
>**For comparison Doge, which has so many coins in circulation that amounts larger than 26 million Doge are actually transacted, has rounding errors recorded in its block chain.  If a new client ever uses a higher-precision float format, their old chain won’t check on that client.  Which would be seen as a bug in the new client, and “corrected” there (by deliberately crippling its accuracy when checking old blocks). In fact it’s a bug in the Doge coin design which will never be fixed because they’ve already committed too much to it.**
>
>Integers.  Even with code that is meticulously maintained and tested for consistency, even where methods errors have been boiled out by somebody’s maniacal obsessive dedication, Integers would have been so much cleaner and easier to check.
