Upgrade this project to make it enable to run on vs2017.

- Retarget .net framework to 4.7.1(AssimpNet/AssimpNet.Interop.Generator/open3mod).
- Upgrade Mono.Cecil.dll from 0.9.4 to 0.10.3 referenced by AssimpNet.Interop.Generator, which downloaded from NuGet.
- Resovle the file access issue in AssimpNet.Interop.Generator.


When upgrade the AssimpNet, project seems to be broken, no idea if AssimpNet was customized.