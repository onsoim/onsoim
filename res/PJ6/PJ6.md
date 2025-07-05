
## [PJ6] A Fuzzing Seed Generation Technique Using Natural Language Processing Model

This research was motivated to generate a good-quality of seed corpus that is directly correlated with the performance of early fuzzing. We compared the performance of a seed corpus that was inferred from various models to help with this problem.

**Objective** Get good quality seed corpus<br>
**Keywords** Data-driven Security, Vulnerability Detection, Fuzzing, Seed Generation, NLP<br>
**Affiliation** HCRL (Hacking and Countermeasure Research Lab)<br>
**Duration** 2021.03-2022.02 (1 year)<br>
**Proportion** 20% (Among 3 people)<br>
**Skills** Python (Tensorflow, Keras), C, Shell, Docker-compose

<br>

### ROLE

1. Generate input/output pair of train dataset
    : Modified AFL 2.5b to save paired value, before and after meaningful mutations
2. Solve various input sizes problem
    - Convert important metadata forward and split with input size
    - Use zero padding if the file size is smaller than the input size
3. Manage experiments using docker-compose
4. Experiments AI models with various combinations of conditions (e.g., Models, batch size, epoch, embedding dimension)

<br>

### OUTPUT

- [P5] A Fuzzing Seed Generation Technique Using Natural Language Processing Model
- [SRC] https://github.com/onsoim/DDRFuzz
- [SRC] https://github.com/onsoim/afl4ddrfuzz
- [C4] CVE-2022-34096

<br>

### WHAT I'VE LEARNED

1. The first experience that proactively participated in an AI project.
2. Apply what I know and experiment them.
