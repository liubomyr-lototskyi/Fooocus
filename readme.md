thx lllyasviel for a basic Fooocus setup.

I noticed a rapidly growing trend where people are actively switching to RTX 5090, RTX 5070, 5080, etc., and suddenly realise that their familiar software does not work due to CUDA incompatibility. This applies to stable-diffusion-webui, fooocus, and a number of other popular programmes. What to do in this situation? Install CUDA 12.8, install library versions that support it, such as torch nightly, and compile packages yourself if they do not yet have native support for the Broadwell generation (RTX 50xx).

What to do with portatives is more complicated.

After spending more than 20 hours testing different versions of CUDA, torch, torchvision, and various versions of wheels, I finally found a working setup.

<h1>Important: it works for me on RTX 5060TI 16GB, but I cannot guarantee that it will work on other 50x versions of NVIDIA.</h1>
