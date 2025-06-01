# MIMO-Networks-With-One-Bit-ADCs-Receiver-Design-and-Communication-Strategies
Simulation and implementation of hybrid blockwise and adaptive threshold receiver architectures for MIMO systems with one-bit ADCs, based on the paper:  "MIMO Networks With One-Bit ADCs: Receiver Design and Communication Strategies", IEEE Trans. on Communications, vol. 70, no. 3, Mar. 2022.

# OneBitADC-MIMO-Receivers

This repository contains Python (Jupyter Notebook) simulations for the paper:

**"MIMO Networks With One-Bit ADCs: Receiver Design and Communication Strategies"**  
*by Abbas Khalili, Farhad Shirani, Elza Erkip, and Yonina C. Eldar*  
Published in IEEE Transactions on Communications, vol. 70, no. 3, March 2022.  
[[IEEE Link]](https://doi.org/10.1109/TCOMM.2021.3133430)

## 📌 Summary

This code implements key simulation results for:

- **Hybrid Blockwise Receiver**: Analog linear combiner + delay network
- **Adaptive Threshold Receiver**: Stream-wise one-bit ADCs with time-varying thresholds

The receivers are evaluated over single-user and multi-user MIMO settings.  
Both high-SNR approximations and finite-SNR numerical simulations are provided.

## 📁 Contents

- `Hybrid_Blockwise_Reciever_and_Adaptive_Treshold_Receiver_for_MIMO_Networks_with_One_Bit_ADCs.ipynb`:  
  Main Jupyter notebook implementing simulations and plotting results, including Fig. 10 and Fig. 12 of the paper.
  
- `MIMO_Networks_With_One-Bit_ADCs_Receiver_Design_and_Communication_Strategies.pdf`:  
  Official IEEE paper containing theoretical background, theorems, and derivations.

## 📊 Reproduced Results

- ✅ High-SNR rate vs number of ADCs (Fig. 10a)
- ✅ Rate gap vs delay length (Fig. 10b)
- ✅ Achievable rate for adaptive threshold receiver (Fig. 12a, 12b)

## 🔧 Requirements

- Python ≥ 3.7
- `numpy`, `matplotlib`, `scipy`

You can install the dependencies with:
```bash
pip install numpy matplotlib scipy
