# MNAD
Minimum Noise Amplitude Deconvolution

MNAD is a blind deconvolution algorithm for enhancing repetitive fault impulses, and similar algorithms include CYCBD, MCKD, MOMEDA, etc. We defined the periodic noise amplitude ratio (PNAR) metric as the minimization criterion for MNAD, and solved MNAD by the backward automatic differential blind deconvolution (BADBD) algorithm we proposed earlier. MNAD can adaptively locate one or more resonance bands excited by local faults. The paper also compares the performance of MNAD and the optimal resonance band selection algorithms (Autogram, IESFOgram).

The GPU model is 1050Ti and the CPU model is I5-8300HQ. The author uses tensorFlow 2.1-GPU. Compared with the implementation of MATLAB, this implementation is significantly faster and may obtain better performance. Please refer to my MATLAB implementation for more examples which can be downloaded from the MATLAB community.

Bo Fang, 2022 05 20.  Research Center of Condition Monitoring and Fault Diagnosis,Southeast University. 130549962@qq.com

Reference
[1] B.Fang, et al., Minimum noise amplitude deconvolution and its application in repetitive impact detection, Structural Health Monitoring,2022,Accepted.
[2] B. Fang, J. Hu, C. Yang, Y. Cao, M. Jia, A blind deconvolution algorithm based on backward automatic differentiation and its application to rolling bearing fault diagnosis, Meas. Sci. Technol. 33 (2022) 025009. https://doi.org/10.1088/1361-6501/ac3fc7


