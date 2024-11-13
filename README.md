# QSeek

## Author: XiangHe and Shaowei Cai

​		     **QSeek** is a local search solver designed for general **mixed-integer quadratic programming** (MIQP) problems, capable of handling cases where quadratic terms appear in the objective function, constraints, or both. It is the updated version of **LS-IQCQP**. Unlike its predecessor, LS-IQCQP, which primarily solves integer quadratic programming (IQP) problems, **QSeek** extends its capabilities to solve not only integer problems but also **mixed-integer** problems.



- To use QSeek,  **run ./QSeek cutoff_time(second) filename.lp**. 

- The paper on **LS-IQCQP** can be found at: https://arxiv.org/abs/2409.19668. The binary source code for **LS-IQCQP** is available at: [wateralxe/LS-IQCQP: A local search solver for integer QCQP problems](https://github.com/wateralxe/LS-IQCQP).
