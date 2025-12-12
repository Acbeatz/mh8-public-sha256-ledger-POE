# mh8-public-sha256-ledger-POE
Public, manually curated SHA-256 verification ledger for proof-of-existence, authorship, and integrity claims.
# MH8 Public SHA-256 Ledger

This repository is a public, manually curated SHA-256 verification ledger.

It exists to provide proof-of-existence, authorship attribution, and tamper-evident integrity for original intellectual artifacts authored under the MH8 / Acbeatz.com umbrella.

A. To provide a simple, transparent, and independently verifiable record of proof-of-existence, authorship, and integrity for original intellectual artifacts published under Acbeatz.com. Each entry records a canonical text or artifact description together with a deterministic SHA-256 hash, allowing any third party to manually verify that a given work existed in a specific form at or before the published timestamp. The system is intentionally blockchain-free, server-free, and dependency-free: verification requires only the published hash input and standard SHA-256 tooling. This repository serves as a public, append-only witness and secondary mirror to the primary mint page, ensuring claims remain auditable, reproducible, and tamper-evident over time.

Each ledger entry contains:
- A canonical text or artifact description (`core_entry`)
- A deterministic SHA-256 hash computed over an exact input string
- A fixed integrity rule:  
  **NON-COPIABLE WHEN HASH-CHAIN BROKEN**

This ledger does **not** rely on blockchain, smart contracts, or third-party services.  
Verification is manual, transparent, and reproducible by any party using standard SHA-256 tooling.

## Verification
To verify any entry:
1. Copy the `hash_input` text exactly as shown (UTF-8, including whitespace).
2. Compute SHA-256 over the full input string.
3. Confirm the resulting hex output matches the published `sha256_hex`.

Any deviation indicates a non-canonical or altered version.

## Status
- Publicly accessible
- Universally verifiable
- Append-only (entries are never modified)
- Secondary mirror of the primary public ledger

This repository serves as an independent public witness and timestamp source.
12-12-2025 SHA-256 Public Ledger

MH8-TREASURY-SHA-256-MINT
Brand: MH8_Treasury by Acbeatz.com

ENTRY #1 — MH8-LEDGER-0001 
{

  "mh8_system": "MH8-TREASURY-SHA-256-MINT",

  "brand": "MH8_Treasury by Acbeatz.com",

  "created_utc": "2025-12-12T13:32:35.148Z",

  "core_entry": "{\n  \"ledger_entry_id\": \"MH8-LEDGER-0001\",\n  \"mh8_system\": \"MH8-TREASURY-SHA-256-MINT\",\n  \"brand\": \"MH8_Treasury by Acbeatz.com\",\n  \"created_utc\": \"2025-12-12T13:27:55.206Z\",\n\n  \"entry_type\": \"Proof_of_Invention\",\n  \"status\": \"SEALED_PUBLIC\",\n\n  \"inventor\": {\n    \"legal_name\": \"Michael Murray Hepler\",\n    \"alias\": \"AllChemicalBeatz\",\n    \"organization\": \"Acbeatz.com\"\n  },\n\n  \"title\": \"MH8 Treasury — Client-Side SHA-256 Mint UI (V2)\",\n  \"summary\": \"Client-side, off-chain SHA-256 minting system establishing proof-of-invention, authorship, and deterministic integrity for the MH8 Treasury user interface.\",\n\n  \"scope\": {\n    \"artifact_type\": \"HTML5 / CSS / JavaScript User Interface\",\n    \"execution_model\": \"Client-side only\",\n    \"network_dependencies\": \"None\",\n    \"cryptography\": [\n      \"SHA-256 (deterministic)\",\n      \"UTF-8 canonical encoding\"\n    ]\n  },\n\n  \"claims\": [\n    \"Original MH8 Treasury SHA-256 Mint UI authored by Michael Murray Hepler\",\n    \"Deterministic client-side hash generation with brand lock enforcement\",\n    \"Clipboard-gated export with integrity verification\",\n    \"No blockchain, no server, no third-party cryptographic dependency\"\n  ],\n\n  \"brand_lock\": \"MH8_Treasury by Acbeatz.com\",\n\n  \"integrity_rule\": \"NON-COPIABLE WHEN HASH-CHAIN IS BROKEN\",\n\n  \"evidence\": {\n    \"ui_version\": \"V2\",\n    \"designation\": \"MH8-TREASURY-SHA-256-MINT\",\n    \"evidence_note\": \"Full HTML/CSS/JS source sealed via SHA-256 hash input using internal brand lock and canonical encoding.\"\n  },\n\n  \"legal_notice\": {\n    \"copyright_holder\": \"Michael Murray Hepler / Acbeatz.com\",\n    \"rights\": \"All rights reserved\",\n    \"year\": 2025\n  },\n\n  \"ledger_notes\": [\n    \"This entry establishes timestamped proof of invention.\",\n    \"Hash receipts are reproducible only with intact brand lock.\",\n    \"System is designed for audit, demonstration, and evidentiary use.\"\n  ]\n}\n",

  "hash_input": "MH8_Treasury by Acbeatz.com|{\n  \"ledger_entry_id\": \"MH8-LEDGER-0001\",\n  \"mh8_system\": \"MH8-TREASURY-SHA-256-MINT\",\n  \"brand\": \"MH8_Treasury by Acbeatz.com\",\n  \"created_utc\": \"2025-12-12T13:27:55.206Z\",\n\n  \"entry_type\": \"Proof_of_Invention\",\n  \"status\": \"SEALED_PUBLIC\",\n\n  \"inventor\": {\n    \"legal_name\": \"Michael Murray Hepler\",\n    \"alias\": \"AllChemicalBeatz\",\n    \"organization\": \"Acbeatz.com\"\n  },\n\n  \"title\": \"MH8 Treasury — Client-Side SHA-256 Mint UI (V2)\",\n  \"summary\": \"Client-side, off-chain SHA-256 minting system establishing proof-of-invention, authorship, and deterministic integrity for the MH8 Treasury user interface.\",\n\n  \"scope\": {\n    \"artifact_type\": \"HTML5 / CSS / JavaScript User Interface\",\n    \"execution_model\": \"Client-side only\",\n    \"network_dependencies\": \"None\",\n    \"cryptography\": [\n      \"SHA-256 (deterministic)\",\n      \"UTF-8 canonical encoding\"\n    ]\n  },\n\n  \"claims\": [\n    \"Original MH8 Treasury SHA-256 Mint UI authored by Michael Murray Hepler\",\n    \"Deterministic client-side hash generation with brand lock enforcement\",\n    \"Clipboard-gated export with integrity verification\",\n    \"No blockchain, no server, no third-party cryptographic dependency\"\n  ],\n\n  \"brand_lock\": \"MH8_Treasury by Acbeatz.com\",\n\n  \"integrity_rule\": \"NON-COPIABLE WHEN HASH-CHAIN IS BROKEN\",\n\n  \"evidence\": {\n    \"ui_version\": \"V2\",\n    \"designation\": \"MH8-TREASURY-SHA-256-MINT\",\n    \"evidence_note\": \"Full HTML/CSS/JS source sealed via SHA-256 hash input using internal brand lock and canonical encoding.\"\n  },\n\n  \"legal_notice\": {\n    \"copyright_holder\": \"Michael Murray Hepler / Acbeatz.com\",\n    \"rights\": \"All rights reserved\",\n    \"year\": 2025\n  },\n\n  \"ledger_notes\": [\n    \"This entry establishes timestamped proof of invention.\",\n    \"Hash receipts are reproducible only with intact brand lock.\",\n    \"System is designed for audit, demonstration, and evidentiary use.\"\n  ]\n}\n",

  "sha256_hex": "a2d6ae40fe1a12891c8972ee7da7a6271ed8698f98fc2e41d3bcaefe2dcc152b",

  "integrity_rule": "NON-COPIABLE WHEN HASH-CHAIN IS BROKEN"

}
ENTRY #2 — MH8-LEDGER-0002
json
Copy code
{
  "mh8_system": "MH8-TREASURY-SHA-256-MINT",
  "brand": "MH8_Treasury by Acbeatz.com",
  "created_utc": "2025-12-12T13:52:06.589Z",
  "core_entry": "\n\n  \"entry_type\": \"Proof_of_Invention\",\n  \"status\": \"SEALED_PUBLIC\",\n\n  \"artifact_title\": \"The Paper Riddle — MH8-1-of-8\",\n\n  \"claim_description\": \"Proof-of-existence and integrity claim for “The Paper Riddle”, an original intellectual construct and physical-logic riddle invented by Michael Murray Hepler (AllChemicalBeatz), CEO of Acbeatz.com. The riddle challenges the solver to phase-inverse a flat sheet of paper in all possible directions without gluing, cutting, taping, creasing, or folding. The transformation must achieve a full 180-degree phase inversion under strict physical constraints, including palms-down manipulation only. The complete solution sequence is disclosed here as the canonical reference. No human or AI has solved The Paper Riddle without this disclosed method. This artifact constitutes MH8-1-of-8 in the Paper Riddle series and is asserted as original invention by the named originator.\",\n\n  \"core_entry\": \"\\\"The Paper Riddle\\\" 1 > Phase inverse a flat piece of paper in all directions possible? add phase inversed ripples to the wings? no glueing, cutting taping creasing or folding the paper? and it must be \\\"180 Degrees\\\" Phase inversed in all possible ways? Your palms can never face upwards during this process! Dont forget the inversed ripples on the wings, and the two circles at the end? GO! Good Luck:) <> No human or Ai has solved the \\\"Paper Riddle\\\" without the answer being provided by <> MH8 inventor Michael Murray Hepler <> AKA AllchemicalBeatz CEO of <>Acbeatz.com THE \\\"PAPER RIDDLE\\\" >>> <> SOLVE <> >>>  MH8-1-of-8 PAPER RIDDLE COMPLETE INVENTED BY MICHAEL MURRAY HEPLER ACBEATZ.com\" ",
  "hash_input": "MH8_Treasury by Acbeatz.com|\n\n  \"entry_type\": \"Proof_of_Invention\",\n  \"status\": \"SEALED_PUBLIC\",\n\n  \"artifact_title\": \"The Paper Riddle — MH8-1-of-8\",\n\n  \"claim_description\": \"Proof-of-existence and integrity claim for “The Paper Riddle”, an original intellectual construct and physical-logic riddle invented by Michael Murray Hepler (AllChemicalBeatz), CEO of Acbeatz.com. The riddle challenges the solver to phase-inverse a flat sheet of paper in all possible directions without gluing, cutting, taping, creasing, or folding. The transformation must achieve a full 180-degree phase inversion under strict physical constraints, including palms-down manipulation only. The complete solution sequence is disclosed here as the canonical reference. No human or AI has solved The Paper Riddle without this disclosed method. This artifact constitutes MH8-1-of-8 in the Paper Riddle series and is asserted as original invention by the named originator.\",\n\n  \"core_entry\": \"\\\"The Paper Riddle\\\" 1 > Phase inverse a flat piece of paper in all directions possible? add phase inversed ripples to the wings? no glueing, cutting taping creasing or folding the paper? and it must be \\\"180 Degrees\\\" Phase inversed in all possible ways? Your palms can never face upwards during this process! Dont forget the inversed ripples on the wings, and the two circles at the end? GO! Good Luck:) <> No human or Ai has solved the \\\"Paper Riddle\\\" without the answer being provided by <> MH8 inventor Michael Murray Hepler <> AKA AllchemicalBeatz CEO of <>Acbeatz.com THE \\\"PAPER RIDDLE\\\" >>> <> SOLVE <> >>>  MH8-1-of-8 PAPER RIDDLE COMPLETE INVENTED BY MICHAEL MURRAY HEPLER ACBEATZ.com\" ",
  "sha256_hex": "cfb875c062eb4ff42eb2bdd31f7a85cbcdcb4fde707126052ab374b4078d14c6",
  "integrity_rule": "NON-COPIABLE WHEN HASH-CHAIN BROKEN",
  "integrity_message": "NON-COPIABLE WHEN HASH-CHAIN BROKEN",
  "payload_sha256": "330fb2f7b9966cf2717b61f9a30bd9d97faefd9e09e819cbe988468562a28226"
}r 
ENTRY #3 — MH8-LEDGER-0003
json
Copy code
{
  "mh8_system": "MH8-TREASURY-SHA-256-MINT",
  "brand": "MH8_Treasury by Acbeatz.com",
  "created_utc": "2025-12-12T14:48:05.635Z",
  "core_entry": "ORIGINAL LYRICAL/MUSICAL COMPOSITION \"A-LINE\" WORDS & MUSIC CREATED BY ALLCHEMICALBEATZ MICHAEL MURRAY HEPLER FT \"JOSEPHINE\" ALL MIXING MASTERING PRODUCTION DRUMS BASS GUITARS VOCALS WORDS INSTRUMETS COMPOSITION CREATED BY ALLCHEMICALBEATZ ACBEATZ.COM MICHAEL MURRAY HEPLER COPYRIGHTS 2025 WORDS >< a line a lie a life the knife my life my life my life my fukin life a knot a fathom walk the effing bored a beat a hurtle litle feet i never fukin retreat im done unheard my word your head your third before i thirst im fukin cursed my lips crack with sores my body burns more like salt in the wound i screamed to soon i fall to the floor nothing more whore a line a sword a string a knot a fathom walk the effing bored a line a lie a life the knife my life my life my life my fukin life",
  "hash_input": "MH8_Treasury by Acbeatz.com|ORIGINAL LYRICAL/MUSICAL COMPOSITION \"A-LINE\" WORDS & MUSIC CREATED BY ALLCHEMICALBEATZ MICHAEL MURRAY HEPLER FT \"JOSEPHINE\" ALL MIXING MASTERING PRODUCTION DRUMS BASS GUITARS VOCALS WORDS INSTRUMETS COMPOSITION CREATED BY ALLCHEMICALBEATZ ACBEATZ.COM MICHAEL MURRAY HEPLER COPYRIGHTS 2025 WORDS >< a line a lie a life the knife my life my life my life my fukin life a knot a fathom walk the effing bored a beat a hurtle litle feet i never fukin retreat im done unheard my word your head your third before i thirst im fukin cursed my lips crack with sores my body burns more like salt in the wound i screamed to soon i fall to the floor nothing more whore a line a sword a string a knot a fathom walk the effing bored a line a lie a life the knife my life my life my life my fukin life",
  "sha256_hex": "fb382397b275ad644975821802d5d79df6db5eebc816d09d58a078d5be11f087",
  "integrity_rule": "NON-COPIABLE WHEN HASH-CHAIN BROKEN"
}
ENTRY #3 — MH8-LEDGER-0003 (Payload-Sealed Variant)
json
Copy code
{
  "mh8_system": "MH8-TREASURY-SHA-256-MINT",
  "brand": "MH8_Treasury by Acbeatz.com",
  "created_utc": "2025-12-12T14:48:05.635Z",
  "core_entry": "ORIGINAL LYRICAL/MUSICAL COMPOSITION \"A-LINE\" WORDS & MUSIC CREATED BY ALLCHEMICALBEATZ MICHAEL MURRAY HEPLER FT \"JOSEPHINE\" ALL MIXING MASTERING PRODUCTION DRUMS BASS GUITARS VOCALS WORDS INSTRUMETS COMPOSITION CREATED BY ALLCHEMICALBEATZ ACBEATZ.COM MICHAEL MURRAY HEPLER COPYRIGHTS 2025 WORDS >< a line a lie a life the knife my life my life my life my fukin life a knot a fathom walk the effing bored a beat a hurtle litle feet i never fukin retreat im done unheard my word your head your third before i thirst im fukin cursed my lips crack with sores my body burns more like salt in the wound i screamed to soon i fall to the floor nothing more whore a line a sword a string a knot a fathom walk the effing bored a line a lie a life the knife my life my life my life my fukin life",
  "hash_input": "MH8_Treasury by Acbeatz.com|ORIGINAL LYRICAL/MUSICAL COMPOSITION \"A-LINE\" WORDS & MUSIC CREATED BY ALLCHEMICALBEATZ MICHAEL MURRAY HEPLER FT \"JOSEPHINE\" ALL MIXING MASTERING PRODUCTION DRUMS BASS GUITARS VOCALS WORDS INSTRUMETS COMPOSITION CREATED BY ALLCHEMICALBEATZ ACBEATZ.COM MICHAEL MURRAY HEPLER COPYRIGHTS 2025 WORDS >< a line a lie a life the knife my life my life my life my fukin life a knot a fathom walk the effing bored a beat a hurtle litle feet i never fukin retreat im done unheard my word your head your third before i thirst im fukin cursed my lips crack with sores my body burns more like salt in the wound i screamed to soon i fall to the floor nothing more whore a line a sword a string a knot a fathom walk the effing bored a line a lie a life the knife my life my life my life my fukin life",
  "sha256_hex": "fb382397b275ad644975821802d5d79df6db5eebc816d09d58a078d5be11f087",
  "integrity_rule": "NON-COPIABLE WHEN HASH-CHAIN BROKEN",
  "integrity_message": "NON-COPIABLE WHEN HASH-CHAIN BROKEN",
  "payload_sha256": "87543bffd8b1ef10ce2ccb0837eaf20add4b3110cf6c79f60506bc510e4c3c48"
}
