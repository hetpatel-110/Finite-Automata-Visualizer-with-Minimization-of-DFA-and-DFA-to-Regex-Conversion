# Finite-Automata-Visualizer-with-Minimization-of-DFA-and-DFA-to-Regex-Conversion

## There are two Zip files each containing 2 different Implementations :
| Project File  | Project Description |
| ------------- | ------------- |
| DFAtoRegex.zip  | For Converting DFA given in JSON format to Minimized DFA  |
| MinDFA.zip  | For Converting DFA given in JSON format to its Regular Expression  |

## Each of the zip files have 3 files :
| File  | Directions |
| ------------- | ------------- |
| input.json  | DFA input in JSON Format  |
| demo.mp4  | A video demo of the implementation  |
| .ipynb file  | Project's implementation, advisable to run it on Google Collab  |


### For Generating Custom DFA the input format in JSON is explained as :
A DFA can be represented by a 5-tuple (Q, ∑, δ, q0, F) where −
| Tuple  | Deinition | JSON |
| ------------- | ------------- | ------------- |
| Q  | Finite set of states  |  states  |
| ∑  | Finite set of symbols called the alphabet  |  letters  |
| δ  | Transition function where δ: Q × ∑ → Q  |  transition_function  |
| q0 | Initial state from where any input is processed (q0 ∈ Q)  |  start_states  |
| F  | Final state/states of Q (F ⊆ Q)  |  final_states  |
