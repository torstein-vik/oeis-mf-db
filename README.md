# OEIS Multiplicative Function Database
***Multiplicative function fatabase created from OEIS data*** <p>
[![Build Status](https://travis-ci.org/torstein-vik/zeta-types-scala.svg?branch=master)](https://travis-ci.org/torstein-vik/zeta-types-scala-db)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


## Installation

1. Clone this repo to your computer
2. Make sure you have SBT (simple build tool) installed on your computer
3. Run 'sbt' in the main directory to start SBT
4. Inside SBT, run 'test' to test the codebase 
5. Run 'test:console' to get an interactive console

Instructions for the actual database setup is not available or decided yet.

Please tell us if this doesn't work, because that means something is wrong with our instructions.

## Current features

TODO...

## Usage Examples

TODO...

## Contributors

_Ask Torstein ([torsteinv64@gmail.com](mailto:torsteinv64@gmail.com)) to add you here if you contribute to this project_
* Torstein Vik

Additionally, we thank all the contributors of ([https://github.com/torstein-vik/multfuncs-db](https://github.com/torstein-vik/multfuncs-db)) for the database specification

## Copyright


This framework is and will remain completely open source, under the GNU General Public License version 3+:

    Copyright (C) 2017, Torstein Vik.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
    

## Languages/Frameworks

* Implementation: Scala
* Build tool: SBT
* Database: MongoDB
* Raw data: Online Encyclopeida of Integer Sequences

## Folder structure

* /project/ -- Part of SBT

* /src/ -- Source directory, where code is edited.
* /src/main/scala -- Main codebase
* /src/test/scala -- Test for the codebase
