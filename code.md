---
layout: page
title: Code
id: code
---

# Code

## Torch7

[Ronan Collobert](http://ronan.collobert.com) from [Idiap](http://www.idiap.ch), [Clement Farabet](http://clement.farabet.net) from [NYU](http://www.nyu.edu) and myself are developing the new version of well-known machine learning library [Torch5](http://torch5.sf.net), an efficient machine learning environment. If you are interested in trying one of the [fastest machine learning library](http://cs.nyu.edu/~koray/files/2011_torch7_nipsw.pdf) check out [Torch7](http://www.torch.ch). 

All the code that I wrote during my PhD for different papers are actually part of a single library that we have developed at CBLL. It is written in [Lush](http://lush.sf.net), an object oriented Lisp derivative language with an integrated compiler that converts [Lush](http://lush.sf.net) code to C code and generates very efficient native code. In order to be able to run our code, you need to install [Lush](http://lush.sf.net) on your system.

## Data
We generally use grayscale Berkeley Natural Images for demonstrating unsupervised learning. We provide 50K randomly extracted 40×40 patches [here](http://cs.nyu.edu/~koray/publis/code/tr-berkeley-N50K-M40x40.mat).

## EbLearn
EbLearn is a machine learning library that is suitable for doing [Energy-Based Learning](http://cs.nyu.edu/~yann/research/ebm/index.html). It contains common modules for doing supervised and unsupervised learning with online stochastic gradient descent. This library can be downloaded [here](http://cs.nyu.edu/~koray/publis/code/eblearn.tar.gz). There is a README file in the root folder that explains how to use this library in [Lush](http://lush.sf.net).


## Packages
We provide the EbLearn library and data (for some experiments) already packaged with these individual archives, so you do not need to worry. The following is a list of papers that we provide some code for. Every experiment can be executed the same way. To run the code, simply enter the following line at [Lush](http://lush.sf.net) prompt.

<html>
<code>
	^L run
</code>
</html>


(yes, with the caret symbol)
All the input parameters for a particular algorithm are contained in a text file named "input" in the package. One can change the parameters in that file to experiment with different setups. It is practical to change the experiment number parameter (exper-nr) when experimenting with different setups.

### Fast Inference in Sparse Coding Algorithms with Applications to Object Recognition
Koray Kavukcuoglu, Marc'Aurelio Ranzato, and Yann LeCun, "**Fast Inference in Sparse Coding Algorithms with Applications to Object Recognition**", Computational and Biological Learning Lab, Courant Institute, NYU, 2008.   
[Arxiv](http://arxiv.org/abs/1010.3467) 
[PDF](http://cs.nyu.edu/~koray/publis/koray-psd-08.pdf) 
[DjVu](http://cs.nyu.edu/~koray/publis/koray-psd-08.djvu) 
[Poster](http://cs.nyu.edu/~koray/publis/koray-psd-08-nips_ws_poster.pdf) 

<html>
<a href="#" onclick="toggle_visibility('bib-koray-psd-08');return false;">bibtex</a>
<div class="bibtex" id="bib-koray-psd-08" >
<pre>
<code>
@techreport { koray-psd-08,
 title = "Fast Inference in Sparse Coding Algorithms with Applications to Object Recognition",
 author = "Kavukcuoglu, Koray and Ranzato, Marc'Aurelio and LeCun, Yann",
 institution = "Computational and Biological Learning Lab, Courant Institute, NYU",
 number = "CBLL-TR-2008-12-01",
 year = "2008",
 }
</code>
</pre>
</div>
</html>

We provide code for the Predictive Sparse Decomposition (PSD) algorithm explained in this paper. Data and input configuration for training PSD with 256 code units is also included in the package.   
[Download (65MB)](http://cs.nyu.edu/~koray/publis/code/psd.tar.gz), 
[Download (without data, 83KB)](http://cs.nyu.edu/~koray/publis/code/psd_code.tar.gz)

### Learning Invariant Features through Topographic Filter Maps
Koray Kavukcuoglu, Marc\'Aurelio Ranzato, Rob Fergus, and Yann LeCun, "**Learning Invariant Features through Topographic Filter Maps**", in Proc. International Conference on Computer Vision and Pattern Recognition (CVPR'09), 2009.   
[PDF](http://cs.nyu.edu/~koray/publis/koray-cvpr-09.pdf) 
[DjVu](http://cs.nyu.edu/~koray/publis/koray-cvpr-09.djvu) 

<html>
<a href="#" onclick="toggle_visibility('bib-koray-cvpr-09');return false;">bibtex</a>
<div class="bibtex" id="bib-koray-cvpr-09" >
<pre>
<code>
@inproceedings { koray-cvpr-09,
 title = "Learning Invariant Features through Topographic Filter Maps",
 author = "Kavukcuoglu, Koray and Ranzato, Marc\'Aurelio and Fergus, Rob and LeCun, Yann",
 booktitle = "Proc. International Conference on Computer Vision and Pattern Recognition (CVPR'09)",
 publisher = "IEEE",
 year = "2009",
}
</code>
</pre>
</div>
</html>

We provide code for Invariant Predictive Sparse Decomposition (IPSD) algorithm explained in this paper. Data and input configuration file for training IPSD with 400 code units in 20 by 20 topographic map is also included in the package.   
[Download (65MB)](http://cs.nyu.edu/~koray/publis/code/ipsd.tar.gz), 
[Download (without data, 84KB)](http://cs.nyu.edu/~koray/publis/code/ipsd_code.tar.gz)

### What is the Best Multi-Stage Architecture for Object Recognition?
Kevin Jarrett, Koray Kavukcuoglu, Marc'Aurelio Ranzato, and Yann LeCun, "**What is the Best Multi-Stage Architecture for Object Recognition?**", in Proc. International Conference on Computer Vision (ICCV'09), 2009.    
[PDF](http://cs.nyu.edu/~koray/publis/jarrett-iccv-09.pdf) 
[DjVu](http://cs.nyu.edu/~koray/publis/jarrett-iccv-09.djvu) 

<html>
<a href="#" onclick="toggle_visibility('bib-jarrett-iccv-09');return false;">bibtex</a>
<div class="bibtex" id="bib-jarrett-iccv-09" >
<pre>
<code>
@inproceedings { jarrett-iccv-09,
 title = "What is the Best Multi-Stage Architecture for Object Recognition?",
 author = "Jarrett, Kevin and Kavukcuoglu, Koray and Ranzato, Marc'Aurelio and LeCun, Yann",
 booktitle = "Proc. International Conference on Computer Vision (ICCV'09)",
 publisher = "IEEE",
 year = "2009",
}
</code>
</pre>
</div>
</html>

For this paper, we provide a limited MATLAB package that only does feature extraction using random convolutional filters followed by a linear logistic regression classifier training. Note that, this source package demonstrates only one of the cases of Table 1 in the paper (RR).   
[Download](http://cs.nyu.edu/~koray/publis/code/randomc101.tar.gz)
