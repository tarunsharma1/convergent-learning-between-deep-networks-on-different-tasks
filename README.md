# convergent-learning
This is my own implementation of a part of this paper http://arxiv.org/pdf/1511.07543v3.pdf 
I am not one of the authors and have no relation or copyrights regarding the original work. This is simply my own implementation of 
a part of the paper I did for a project, and found it useful hence I am sharing.


This is the implementation of the semi matching of activations from two VGG 16s. The net can be substituted by any other network. I
have followed the same approach as described in the paper of taking max correlations and then the mean.

This can be used to compare features learnt between two networks. This will allow you to analyse for yourself in which layer 
feature representations differ the most on networks trained on say two different tasks.

For a thorough understanding of the procedure and its implications I recommend going through the paper. It is a brilliant paper. In 
the paper the comparison is done between two AlexNets initiallized from random weights. But the correlation can be done 
between networks trained on different tasks also.

The paper was published at ICLR 2016 and the authors are Yixuan Li , Jason Yosinski , Jeff Clune, Hod Lipson, & John Hopcroft
. Again I have nothing to do with the original work. This is just my own implementation of a part of their work over which I hold
no rights. 




