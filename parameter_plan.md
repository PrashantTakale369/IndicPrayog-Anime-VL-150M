1. Parameter Budget Plan


- Training resolution : 256x256 (RGB)
- VAE Downsampling : f = 8  -> latent grid = 32x32 
- latent Channels : 4
- DiT Patch Size : 2 -> sequence length = 32x32 / 2x2 = 16x16 = 256 tokens ';

( 256 token is the sweet spot ) 



2. VAE = 18.2M parameters
3. Text Encoder = 10.25M parameters
4. DiT = 111.76M parameters

> Total = 140.21M parameters [ ~150 M parameters is the sweet spot for a 256x256 model ]                      