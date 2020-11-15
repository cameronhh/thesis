# An Exploration of the Libra Testnet
*Information accurate as of 20/06/2020.*

Libra is a blockchain-based payments platform created and backed by Facebook
and their subsidiary company, Novi. On 
June 18, 2019 the Libra testnet was launched, allowing developers to interact with
the platform. This thesis is an exploration of such testnet. It investigates the data
which is available to be queried on the testnet and what can be learnt from it.
The way in which the testnet has changed over the first 12 months of its development is 
also explored.

Libra uses a leader-based Byzantine Fault-Tolerant consensus protocol. The role of the 
leader in leader-based consensus protocols is to receive votes from other nodes in 
the network, and propagate messages detailing the success/failure of the voting for that round.
Despite claiming to be random, the main contribution of this thesis is the discovery 
that Libra uses a reputation based algorithm for the selection of a round leader in 
consensus. Validator nodes - the name given to those whose computers
participate in the consensus - were less frequently chosen as round leader 
when they had a greater latency of communication with the rest of the network,
causing their votes to be counted less often.

Final Grade: 6/7
