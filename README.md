A simple cryptographic excercise - decrypting messages encrypted by the Ceasar Cipher. Returns the shift and the plain text message.

Uses a simple heuristic - chooses the shift which produces the most valid English words in the plain text.

Classes `PlaintextMessage`, `CiphertextMessage` as well as the methods `apply_shift` and `bulid_shift_dict` of the `Message` class are my implementatnion. The rest was provided by MITx: 6.00.1x course organizers.
