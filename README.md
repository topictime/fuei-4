# fuei-4
        "name": "Avail Descriptor",
                    "identifier": "FUEI",                     # <-- Changed
                    "provider_avail_id": 0
        if cue.descriptors:
            cue.descriptors[0].identifier = "FUEI"  # Changed
        cue.encode()


