# objectives 

a complete description of complex molecules inludes information about their structure and their dynamics. We may be insterested in the following questions" 

1. what are the strutural isomers possible? 

2. is there any relevant hierarchy among these isomers? 

3. what are the transition paths between them. 

   

how could we efficiently describte the free energy landscape for small and large modecules. 





# Energy landscapes: calculating pathways and rates

## the stationary points 

1. Introduction 

   to obtaion termodynamic or kinetic properties for modelcules 

   1. if large PE(potential energy) barriers: rare transitions. 
   2. alternatives to treat the kinetics 

   to review discrete path sampling approach  where coarse-graining is achieved using stationary points of the underlying **potential energy surface**(PES). 

   1. small molecules	
      1. separate partition functions . isomers as local minima on PES amnd separted by the berries which is large compare to $k_bT$
      2. still apply to larger systems but the # of minima grows exponentially with the # atoms. 
      3. to distinguish minima by an order parameter . 
      4. superposition approach has several attractive features. 
         1. the contributions to any thermodynamic property calculated from the rsulting partition function can be broken dwon intwo terms correspoinding to different local minima, or regions of configuration space. 
         2. total partition function in this case is naturally [ergodic](https://en.wikipedia.org/wiki/Ergodicity) (???).
         3. [a systemativ way to assure proper sampling of LM]transforming the PES into the basins of attraction of local minima also provide the basis for **basin-hopping global optimisation algorithm**. 
            1. move by minimization of PE in configuration space 
            2. reject/accpt moves between local mimima is decided by a metropolis criterion. 
         4. method used in this paper 
            1. obtain PED of local minima by Wang-Landau-type sampling
            2. calculate average anharmonic vibrational partition functions 
         5. LM on the PES are stationary points(gradient == 0 ? )
         6. two LM ARE ADJACENT AND CONNECTED BY THE TRANSITION STATE, IF 

2. Discrete path sampling [DPS]  based on stationary states. 

   1. Rate constant formulations 
      1. single-exponential, two-state kinetics 
      2. assumption: the dynamics betwwen adjacemnt KM are **Markovian**  so that the system loses its memory of the previous mimimum before it makes another transtion. 
      3. intermediate region is included hte sum over rate constznts for process crossing the A/B boundary. 
      4. Discrete paths is defined as the LM-transition state-LM-...- LM sequences. 
      5. how to sample path1 s sffectively. 
   2. Building stationary point databases 
   3. Calculation of rate constants 

3. Characterising stationary points and pathways 252

4. Disconnectivity graphs

d

