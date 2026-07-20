# Red-Black Tree in C

<img width="4201" height="2378" alt="rbt" src="https://github.com/user-attachments/assets/c9d096fd-f4dd-4738-a26b-330561acc59e" />


A complete, production-grade **Red-Black Tree (RBT)** implementation in C based on the specifications from *Introduction to Algorithms* (CLRS).

---

## Features

- **Full RBT Operations:** Insertion, search, and deletion with dynamic balance fixups (rotations & recoloring).
- **CLRS Standard:** Uses a dedicated `NIL` sentinel node for unified edge case handling and strict black-height guarantees.
- **Graphviz Export:** Includes automatic `.dot` graph generation to render tree structures into SVG/PNG diagrams with visual node coloring (`RED` / `BLACK`).
- **Atari 2600 Dataset:** Includes a sample benchmark dataset with 50 classic Atari 2600 titles to demonstrate balanced tree operations and visual exports.

---

##  Project Structure

```text
.
├── RedBlackTree_Final.c   # Main implementation (RBT operations + Graphviz export + Main)
├── rbt_preview.png        # Visual demonstration image
└── README.md              # Documentation
