# [Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]

Article Illustrations
Simulation Experiment SISO
Figure 4 shows the bit error rate (BER) performance of uncoded QPSK transmission over a Rayleigh fading channel in SISO. The bit error rates for BPSK and QPSK decrease linearly with increasing unit signal-to-noise ratio (SNR) on a double logarithmic scale, which aligns with theoretical predictions. The results indicate that even at a relatively high SNR of 20 dB, the BER reaches 2.035 × 10−3, which is still quite high. In other words, an SISO system does not provide diversity just by using one transmitter and receiver antenna, hence the high BER.
Figure 5 presents the BER-SNR plot for a dual-antenna SIMO Rayleigh fading channel with MRC combining. Similarly, as the reciprocal of SNR decreases, the blue and red curves represent the approximate linear decrease in BER for BPSK and QPSK, respectively. Note that instead of using approximations from [1], more precise analytical expressions were found in [3] as used in simulations, such as Equation 5.
The main difference between theoretical values and actual values is due to estimation errors in the joint bounds and the randomness of the MCM. Increasing the sample size can reduce errors. It has been proven that when the reciprocal of SNR decreases, the diversity provided by multiple antennas in a multi-antenna system provides a second-order decay to the dual-antenna receiver.
Figure 6 shows the array gain and diversity gain for a 1 × 2 system. It can be concluded that as SNR approaches infinity, both gains tend to reach 2, equal to the expected number of receive antennas.
MISO
1)MRT: At the transmitter end, MRT transmission is a viable method through perfect CSIT. Figure 7 compares the theoretical and actual error rates for a 2-to-1 MISO system adopting the MRT strategy. Simulation results show that the theoretical error rate is inversely proportional to the square of SNR, consistent with the 1 x 2 SIMO MRC case. The sources of error are the same (joint bounds and MCM), which can be reduced by expanding the dataset. As in the MRC case, two degrees of freedom in the transmitter provide significant enhancement in BER inversely proportional to SNR squared.
Array gain and diversity gain are shown in Figure 8, which become close to the number of transmit antennas as SNR increases. The results match expectations. MRT utilizes transmitter beamforming to achieve signal diversity at the transmitter while maintaining the same beamforming and diversity gains as MRC. However, in some cases, such as rapid movement, it may not be possible to meet the perfect CSIT requirements. The Alamandro scheme can overcome this issue.
Figure 11 compares the error rate performance of all models used in this task. The error rate in a fading channel is significantly higher than that in an additive white Gaussian noise (AWGN) channel, where multi-antenna systems can provide channel and signal diversity, thereby reducing the error rate. Additionally, SIMO and MISO systems introduce array gain and diversity gain, respectively. Array gain describes the improvement in average SNR relative to single-branch SNR, while diversity gain examines the enhancement in BER relative to single-branch SNR. The former is related to CSI knowledge, while the latter is associated with channel counting. It can be interpreted that the multi-antenna approach reduces system uncertainty (noise and channel) by leveraging diversity, and both gains can be quantified improvements.
The conclusion of this study compares the bit error performance of SISO, SIMO and MISO systems based on uncoded and Alamplitude QPSK modulation under Rayleigh fading channels. It has been proven that multi-antenna diversity methods can provide additional reliability to wireless communication systems with appropriate transmission splitting and reception combining schemes. Additionally, array gain and diversity gain are related to channel state information (CSI) knowledge and channel diversity respectively. For the SIMO system, if noise is uncorrelated AWGN, MRC combining is optimal. At the receiver, MRT transmission can achieve the same performance as MRC with CSIT. If CSIT is unavailable but the channel remains constant over several symbol periods (2 for two antennas), then the Alaampti scheme can achieve the same diversity gain without array gain. Therefore, for a 2 × 1 MISO system, the Alamplitude SNR is 3 dB worse than MRC and MRT. The main limitation lies in (1) considering only two antennas at the receiver and transmitter for SIMO and MISO respectively (2) no research was conducted on MIMO systems. By increasing the number of bits and generating more traversal channels, the random errors in MCM can be further reduced. The system can be extended to more antenna cases by using code provided in the appendix.

## Images

![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](01.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](02.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](03.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](04.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](05.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](06.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](07.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](08.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](09.jpg)
![[Ruili Channel] SISO/SIMO/MISO Link-Level Performance Evaluation [with MATLAB Code]](10.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
