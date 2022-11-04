# Manual mapping DLL injection

 1. Load raw binary data
 2. Map sections into target process 
 3. Inject loader Shellcode 
 4. Relocate
 5. Fix Imports
 6. execute TLS callbacks 
 7. Call dllMain
 8. Clean UP
