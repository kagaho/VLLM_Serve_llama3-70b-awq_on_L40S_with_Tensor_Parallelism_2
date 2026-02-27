rteixeira@shockwave:~$ podman exec -it fervent_lovelace vllm collect-env
```
Collecting environment information...
==============================
        System Info
==============================
OS                           : Ubuntu 22.04.5 LTS (x86_64)
GCC version                  : (Ubuntu 11.4.0-1ubuntu1~22.04.3) 11.4.0
Clang version                : Could not collect
CMake version                : Could not collect
Libc version                 : glibc-2.35

==============================
       PyTorch Info
==============================
PyTorch version              : 2.9.1+cu129
Is debug build               : False
CUDA used to build PyTorch   : 12.9
ROCM used to build PyTorch   : N/A

==============================
      Python Environment
==============================
Python version               : 3.12.12 (main, Oct 10 2025, 08:52:57) [GCC 11.4.0] (64-bit runtime)
Python platform              : Linux-6.18.13-200.fc43.x86_64-x86_64-with-glibc2.35

==============================
       CUDA / GPU Info
==============================
Is CUDA available            : True
CUDA runtime version         : 12.9.86
CUDA_MODULE_LOADING set to   :
GPU models and configuration :
GPU 0: NVIDIA L40S
GPU 1: NVIDIA L40S

Nvidia driver version        : 580.119.02
cuDNN version                : Could not collect
HIP runtime version          : N/A
MIOpen runtime version       : N/A
Is XNNPACK available         : True

==============================
          CPU Info
==============================
Architecture:                            x86_64
CPU op-mode(s):                          32-bit, 64-bit
Address sizes:                           46 bits physical, 57 bits virtual
Byte Order:                              Little Endian
CPU(s):                                  128
On-line CPU(s) list:                     0-127
Vendor ID:                               GenuineIntel
Model name:                              INTEL(R) XEON(R) PLATINUM 8562Y+
CPU family:                              6
Model:                                   207
Thread(s) per core:                      2
Core(s) per socket:                      32
Socket(s):                               2
Stepping:                                2
BogoMIPS:                                5600.00
Flags:                                   fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc art arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc cpuid aperfmperf tsc_known_freq pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid dca sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch cpuid_fault epb cat_l3 cat_l2 cdp_l3 cdp_l2 ssbd mba ibrs ibpb stibp ibrs_enhanced tpr_shadow flexpriority ept vpid ept_ad fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid cqm rdt_a avx512f avx512dq rdseed adx smap avx512ifma clflushopt clwb intel_pt avx512cd sha_ni avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves cqm_llc cqm_occup_llc cqm_mbm_total cqm_mbm_local split_lock_detect user_shstk avx_vnni avx512_bf16 wbnoinvd dtherm ida arat pln pts hfi vnmi avx512vbmi umip pku ospke waitpkg avx512_vbmi2 gfni vaes vpclmulqdq avx512_vnni avx512_bitalg avx512_vpopcntdq la57 rdpid bus_lock_detect cldemote movdiri movdir64b enqcmd fsrm md_clear serialize tsxldtrk pconfig arch_lbr ibt amx_bf16 avx512_fp16 amx_tile amx_int8 flush_l1d arch_capabilities
Virtualization:                          VT-x
L1d cache:                               3 MiB (64 instances)
L1i cache:                               2 MiB (64 instances)
L2 cache:                                128 MiB (64 instances)
L3 cache:                                120 MiB (2 instances)
NUMA node(s):                            2
NUMA node0 CPU(s):                       0,2,4,6,8,10,12,14,16,18,20,22,24,26,28,30,32,34,36,38,40,42,44,46,48,50,52,54,56,58,60,62,64,66,68,70,72,74,76,78,80,82,84,86,88,90,92,94,96,98,100,102,104,106,108,110,112,114,116,118,120,122,124,126
NUMA node1 CPU(s):                       1,3,5,7,9,11,13,15,17,19,21,23,25,27,29,31,33,35,37,39,41,43,45,47,49,51,53,55,57,59,61,63,65,67,69,71,73,75,77,79,81,83,85,87,89,91,93,95,97,99,101,103,105,107,109,111,113,115,117,119,121,123,125,127
Vulnerability Gather data sampling:      Not affected
Vulnerability Ghostwrite:                Not affected
Vulnerability Indirect target selection: Not affected
Vulnerability Itlb multihit:             Not affected
Vulnerability L1tf:                      Not affected
Vulnerability Mds:                       Not affected
Vulnerability Meltdown:                  Not affected
Vulnerability Mmio stale data:           Not affected
Vulnerability Old microcode:             Not affected
Vulnerability Reg file data sampling:    Not affected
Vulnerability Retbleed:                  Not affected
Vulnerability Spec rstack overflow:      Not affected
Vulnerability Spec store bypass:         Mitigation; Speculative Store Bypass disabled via prctl
Vulnerability Spectre v1:                Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:                Mitigation; Enhanced / Automatic IBRS; IBPB conditional; PBRSB-eIBRS SW sequence; BHI BHI_DIS_S
Vulnerability Srbds:                     Not affected
Vulnerability Tsa:                       Not affected
Vulnerability Tsx async abort:           Not affected
Vulnerability Vmscape:                   Mitigation; IBPB before exit to userspace

==============================
Versions of relevant libraries
==============================
[pip3] flashinfer-python==0.6.3
[pip3] numpy==2.2.6
[pip3] nvidia-cublas-cu12==12.9.1.4
[pip3] nvidia-cuda-cupti-cu12==12.9.79
[pip3] nvidia-cuda-nvrtc-cu12==12.9.86
[pip3] nvidia-cuda-runtime-cu12==12.9.79
[pip3] nvidia-cudnn-cu12==9.10.2.21
[pip3] nvidia-cudnn-frontend==1.18.0
[pip3] nvidia-cufft-cu12==11.4.1.4
[pip3] nvidia-cufile-cu12==1.14.1.1
[pip3] nvidia-curand-cu12==10.3.10.19
[pip3] nvidia-cusolver-cu12==11.7.5.82
[pip3] nvidia-cusparse-cu12==12.5.10.65
[pip3] nvidia-cusparselt-cu12==0.7.1
[pip3] nvidia-cutlass-dsl==4.4.0
[pip3] nvidia-cutlass-dsl-libs-base==4.4.0
[pip3] nvidia-ml-py==13.590.48
[pip3] nvidia-nccl-cu12==2.27.5
[pip3] nvidia-nvjitlink-cu12==12.9.86
[pip3] nvidia-nvshmem-cu12==3.3.20
[pip3] nvidia-nvtx-cu12==12.9.79
[pip3] pyzmq==27.1.0
[pip3] torch==2.9.1+cu129
[pip3] torchaudio==2.9.1+cu129
[pip3] torchvision==0.24.1+cu129
[pip3] transformers==4.57.6
[pip3] triton==3.5.1
[conda] Could not collect

==============================
         vLLM Info
==============================
ROCM Version                 : Could not collect
vLLM Version                 : 0.16.0
vLLM Build Flags:
  CUDA Archs: 7.0 7.5 8.0 8.9 9.0 10.0 12.0; ROCm: Disabled
GPU Topology:
  	GPU0	GPU1	NIC0	NIC1	CPU Affinity	NUMA Affinity	GPU NUMA ID
GPU0	 X 	NODE	SYS	SYS	0,2,4,6,8,10	0		N/A
GPU1	NODE	 X 	SYS	SYS	0,2,4,6,8,10	0		N/A
NIC0	SYS	SYS	 X 	PIX
NIC1	SYS	SYS	PIX	 X

Legend:

  X    = Self
  SYS  = Connection traversing PCIe as well as the SMP interconnect between NUMA nodes (e.g., QPI/UPI)
  NODE = Connection traversing PCIe as well as the interconnect between PCIe Host Bridges within a NUMA node
  PHB  = Connection traversing PCIe as well as a PCIe Host Bridge (typically the CPU)
  PXB  = Connection traversing multiple PCIe bridges (without traversing the PCIe Host Bridge)
  PIX  = Connection traversing at most a single PCIe bridge
  NV#  = Connection traversing a bonded set of # NVLinks

NIC Legend:

  NIC0: mlx5_0
  NIC1: mlx5_1

==============================
     Environment Variables
==============================
NVIDIA_VISIBLE_DEVICES=all
TORCH_CUDA_ARCH_LIST=7.0 7.5 8.0 8.9 9.0 10.0 12.0
VLLM_USAGE_SOURCE=production-docker-image
NVIDIA_REQUIRE_CUDA=cuda>=12.9 brand=unknown,driver>=535,driver<536 brand=grid,driver>=535,driver<536 brand=tesla,driver>=535,driver<536 brand=nvidia,driver>=535,driver<536 brand=quadro,driver>=535,driver<536 brand=quadrortx,driver>=535,driver<536 brand=nvidiartx,driver>=535,driver<536 brand=vapps,driver>=535,driver<536 brand=vpc,driver>=535,driver<536 brand=vcs,driver>=535,driver<536 brand=vws,driver>=535,driver<536 brand=cloudgaming,driver>=535,driver<536 brand=unknown,driver>=550,driver<551 brand=grid,driver>=550,driver<551 brand=tesla,driver>=550,driver<551 brand=nvidia,driver>=550,driver<551 brand=quadro,driver>=550,driver<551 brand=quadrortx,driver>=550,driver<551 brand=nvidiartx,driver>=550,driver<551 brand=vapps,driver>=550,driver<551 brand=vpc,driver>=550,driver<551 brand=vcs,driver>=550,driver<551 brand=vws,driver>=550,driver<551 brand=cloudgaming,driver>=550,driver<551 brand=unknown,driver>=560,driver<561 brand=grid,driver>=560,driver<561 brand=tesla,driver>=560,driver<561 brand=nvidia,driver>=560,driver<561 brand=quadro,driver>=560,driver<561 brand=quadrortx,driver>=560,driver<561 brand=nvidiartx,driver>=560,driver<561 brand=vapps,driver>=560,driver<561 brand=vpc,driver>=560,driver<561 brand=vcs,driver>=560,driver<561 brand=vws,driver>=560,driver<561 brand=cloudgaming,driver>=560,driver<561 brand=unknown,driver>=565,driver<566 brand=grid,driver>=565,driver<566 brand=tesla,driver>=565,driver<566 brand=nvidia,driver>=565,driver<566 brand=quadro,driver>=565,driver<566 brand=quadrortx,driver>=565,driver<566 brand=nvidiartx,driver>=565,driver<566 brand=vapps,driver>=565,driver<566 brand=vpc,driver>=565,driver<566 brand=vcs,driver>=565,driver<566 brand=vws,driver>=565,driver<566 brand=cloudgaming,driver>=565,driver<566 brand=unknown,driver>=570,driver<571 brand=grid,driver>=570,driver<571 brand=tesla,driver>=570,driver<571 brand=nvidia,driver>=570,driver<571 brand=quadro,driver>=570,driver<571 brand=quadrortx,driver>=570,driver<571 brand=nvidiartx,driver>=570,driver<571 brand=vapps,driver>=570,driver<571 brand=vpc,driver>=570,driver<571 brand=vcs,driver>=570,driver<571 brand=vws,driver>=570,driver<571 brand=cloudgaming,driver>=570,driver<571
LD_LIBRARY_PATH=/usr/local/lib/python3.12/dist-packages/cv2/../../lib64:/usr/local/nvidia/lib64:/usr/local/cuda/lib64:/usr/local/cuda/lib64
CUDA_VERSION=12.9.1
NVIDIA_DRIVER_CAPABILITIES=compute,utility
PYTORCH_NVML_BASED_CUDA_CHECK=1
TORCHINDUCTOR_COMPILE_THREADS=1
TORCHINDUCTOR_CACHE_DIR=/tmp/torchinductor_root
VLLM_WORKER_MULTIPROC_METHOD=spawn
```
