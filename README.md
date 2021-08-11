<p align= "center">
<a href="https://colab.research.google.com/drive/1W1s7Xwe1MbEImNdMzSt6keNhLAdgOJwR?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a>
</p>

# Region Proposal Network In Faster-RCNN

*My implementation is heavily based on the* **“**[**Guide to build Faster RCNN in PyTorch**](https://medium.com/@fractaldle/guide-to-build-faster-rcnn-in-pytorch-95b10c273439)**”** *article.*

Two-stage detectors consist of two stages (duh), First stage (network) is used to suggest the region of interest (region of the image where the object might be) and these proposals are then sent to another network (stage two) for the actual object classification of proposals and offset regression (More on this later). On the other hand, one-stage detectors are really fast (in the terms of prediction and processing) but they usually have less accuracy than two-stage detectors (there is always a trade-off between speed and correctness).

Read full blog here: [Region Proposal Network(RPN) (in Faster RCNN) from scratch in Keras](https://martian1231-py.medium.com/region-proposal-network-rpn-in-faster-rcnn-from-scratch-in-keras-1311c67c13cf)