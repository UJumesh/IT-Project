# Mess Management System (C)

A console-based academic mess-management project implemented in C. The source is currently stored in the file [`Code`](Code).

## Functionality in the source
- Register and log in users
- Add and view menu items by day
- Display breakfast, lunch, and dinner timings
- Submit and view feedback
- Save/load user, menu, and feedback data in a local `data.bin` file

## Running locally

The source has no `.c` extension in this repository. Download it and save it locally as `mess_management.c`, then compile with a C compiler:

```bash
gcc mess_management.c -o mess-management
./mess-management
```

**Status:** Academic prototype; compilation and runtime are not verified here. The source contains inconsistent day-name spellings/casing and stores passwords as plaintext in a binary file. Do not use it for sensitive or production data.
