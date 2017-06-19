# Cloud Hopfield Neural Network
Cloud Hopfield Neural Network (CHNN) is a modified retreival algorithm for HNN. Proposed by [Narotam Singh](https://github.com/narotamsingh) and [Amita Kapoor](http://www.dramitakapoor.com) in 2015.

In CHNN retreival algorithm, we first divide the HNN in to cloud, with each cloud having unique r neurons, (these neurons can be assigned to the cloud in a sequential manner or they can be distributed throughout the network), all the neurons belonging to a cloud are synchronously updated. 

Our results demonstrate that when we present the network with higher distortion in the corrupted version of the fundamental pattern the time taken to converge to the correct fundamental memory for CHNN is less as compared to AHNN, also it converges to the correct fundamental memory significantly more times than AHNN. Lastly, as long the size of cloud is not large the network does not suffer from oscillations of state as well. Thus, CHNN is a better retrieval algorithm as compared to both SHNN and AHNN. 
The complete paper can be accessed at: <http://ieeexplore.ieee.org/document/7275610/>
