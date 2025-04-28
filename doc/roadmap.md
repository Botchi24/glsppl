# Project Roadmap

## 1. Motivation

**Problem:**
- enable different versions (target platforms) of a GLSP graph editor
- use variability categories (SPL)

**Goals:**
- SPL architecture for GLSP-based graph editor
- manage variability using feature model and viewpoint model

## 2. Structure

**related work analysis:** sirius, ...

**analysis:** variability modeling techniques for graph editors

**design:** extension/refinement of the architecture

**implementation:** core assets + variability points

**evaluation:** prototype

## 3. Methodology

- **Domain Engineering:**
    - **Domain Analysis:** 
        - identify common and variable features across potential graph editor products
        - literature review on graph editor variability and SPL techniques
    - **Feature Modeling:** 
        - extend/refine feature model with the identified variability (FeatureIDE)
    - **Architecture Design:** 
        - extend/refine architecture with variability points (viewpoint modeling, architectural patterns for SPLs)
        - extend/refine variability implementation mechanisms (configuration, plugins, code generation)
- **Application Engineering:**
    - extend/refine process of configuring (config manager) 
    - generate specific editor products based on feature selections (featureIDE)

