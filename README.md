# Tilemap_with_data_at_0000
Demo how to have your source data in the same SLOTs as L2

This small example shows how you can read and write from different banks when drawing to Layer2

We can read our source bitmap data at $0000 - $3fff and then write to the same memory address rang
but to Layer2! 

