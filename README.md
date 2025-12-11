# Quantum-NLP-

This shows how to encode text into quantum states using rotation-based embeddings.
It demonstrates three ideas in the simplest possible way:

Classical NLP → Bag-of-Words → Scalar angle

Quantum embedding → Ry(θ) rotation → ⟨Z⟩ feature

Expressivity check → Approximate Quantum Fisher Information (QFIM)

🚀 Overview

Each sentence is converted into a bag-of-words vector.

The vector is compressed into a single rotation angle θ.

A single qubit is rotated with Ry(θ) to produce a quantum state.

The expectation value ⟨Z⟩ of that state serves as the sentence embedding.

A minimal QFIM approximation measures how sensitive the embedding is to θ (i.e., its expressivity).

This keeps the entire pipeline transparent, minimal, and easy to explain.
