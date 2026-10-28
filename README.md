# Fault-System Identification from Relocated Earthquake Hypocentres

## Overview

This project outlines a data-analysis workflow for examining spatial patterns in relocated earthquake hypocentres and investigating whether those patterns may be consistent with fault geometry.

## Proposed workflow

1. Prepare relocated hypocentre coordinates and review their spatial coverage and coordinate reference system.
2. Apply DBSCAN and hierarchical clustering to examine possible spatial groupings. These methods are exploratory and do not, by themselves, identify geological faults.
3. Use Principal Component Analysis (PCA) and Singular Value Decomposition (SVD) to examine the orientation and geometry of selected hypocentre groupings.
4. Compare the resulting patterns with the input data and document sensitivity to analysis choices before drawing geological interpretations.

## Current status

This repository currently contains a workflow overview only. No analysis code, dataset, executed results, or tests are included, so the proposed methods have not been demonstrated here.

## Limitations

Cluster patterns and principal axes are geometric descriptions of the input points. They are not proof of a fault, and interpretation would require suitable data, documented parameters, geological context, and validation.
