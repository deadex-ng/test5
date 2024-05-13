# Petl Errors Documentation

1. ## Feature not supported: "autoServerMode && (readOnly || fileLockMethod == NO || fileLockMethod == SERIALIZED || fileLockMethod == FS || inMemory)
This was fixed by deleting `rm petl.mv.db` and `rm petl.trace.db` in `/opt/petl/data` on the Upper Neno server
