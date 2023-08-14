# CT_Helper

Carbon trading data does not exhibit either stationary or highly volatile
time series behavior, making it challenging to analyze and model on carbon
trading data. To address this issue, we first train an optimal trading strategy
model using reinforcement learning. Then, the trained model is evaluated
using data from 8 authentic carbon trading institutions. Next, we introduce
the classic time series trading models as the baseline for comparison. In the
experimental evaluation, the model we proposed achieves profitability in the
majority of the trading scenarios. Compared to the Buy-and-Hold strategy,
CT Helper yields superior results. The experimental results demonstrate
that our proposed AI-assisted carbon trading models achieve good performance, highlighting the practical significance of real-world applications for
carbon trading assistance.
![image](https://github.com/23kaka6/CT_Helper/assets/121601339/b26b7b3e-1ef4-4fac-9b43-be1c56946e6f)



## model
The model folder, stores models that have been trained using six different sampling methods, using data sourced from the same eight carbon trading institutions.
In the six sampling methods, all parameters are configured the same, except for vanilla and MLP, which do not have a fixed window size. Therefore, no window size is set for these methods. For the other sampling methods, the window size is set to 10. The remaining parameters are set as follows: batch_size=16, gamma=0.1, RMSize (Replay Memory Size)=16.
