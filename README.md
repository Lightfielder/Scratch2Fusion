# Scratch to Fusion

Doc Created: 2024-04-08  
Doc Updated: 2026-09-06  
Doc By: Andrew Hazelden <andrew@andrewhazelden.com>  

## Overview

The "Scratch2Fusion" script imports Assimilate Scratch/LiveFX content into BMD Fusion Studio. Each clip is created as a Loader node in Fusion. The filename, tile color, and comment attributes are assigned to each node.

----

The "Scratch2Resolve" script imports Assimilate Scratch/LiveFX content into BMD Resolve Studio. Each clip is created as a media pool item. The filename, clip color, and comment attributes are assigned to each media pool item.

## Changelog

Updated the Python scripts to support Python v3.6 - 3.15+ by switching to the importlib Python module. This solves an issue where the Resolve API's previously recommended Python "imp" module usage that was depreciated at Python v3.11.
