## Migration

### Migrating from nfc_uid
I decided to go from only scanning the hwid to creating a multitool. <br>
This is no promise for maintain or expansion!!!

How to use hwid scans:

    import nfcmodule
    
    hwid_reader = nfcmodule.hwid.READER()
    hwid_reader.read()