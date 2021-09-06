This directory contains the Enron-Spam datasets, as described in the 
paper:

V. Metsis, I. Androutsopoulos and G. Paliouras, "Spam Filtering with 
Naive Bayes - Which Naive Bayes?". Proceedings of the 3rd Conference 
on Email and Anti-Spam (CEAS 2006), Mountain View, CA, USA, 2006.

The "preprocessed" subdirectory contains the messages in the 
preprocessed format that was used in the experiments of the paper.
Each message is in a separate text file. The number at the beginning
of each filename is the "order of arrival".

The "raw" subdirectory contains the messages in their original form. 
Spam messages in non-Latin encodings, ham messages sent by the owners 
of the mailboxes to themselves (sender in "To:", "Cc:", or "Bcc" 
field), and a handful of virus-infected messages have been removed, 
but no other modification has been made. The messages in the "raw" 
subdirectory are more than the corresponding messages in the 
"preprocessed" subdirectory, because: (a) duplicates are preserved 
in the "raw" form, and (b) during the preprocessing, ham and/or spam 
messages were randomly subsampled to obtain the desired ham:spam 
ratios. See the paper for further details.

The Enron-Spam datasets are available from: 
<http://www.iit.demokritos.gr/skel/i-config/> and
<http://www.aueb.gr/users/ion/publications.html>.

The paper is available from:
<http://www.ceas.cc/> and 
<http://www.aueb.gr/users/ion/publications.html>.

V. Metsis, I. Androutsopoulos and G. Paliouras  

This file last updated: June 19, 2006.
