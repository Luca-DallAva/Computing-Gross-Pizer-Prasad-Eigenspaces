# Computing-Gross-Pizer-Prasad-Eigenspaces
We provide algorithms in Magma for computing the eigenspaces of quaternionic modular forms with level structure given by Special (Bass) order. We work with definite quaternion algebras.


A nice and fast way to produce newforms is via the command Newforms(label) (https://magma.maths.usyd.edu.au/magma/handbook/text/1654#18846). One can call all the newforms with trivial character, level 'N' and weight 'w' as Newforms('Nkw'), e.g. Newforms('75k2') produces a list of normalized new modular forms of level 75 and weight 2.


GrossPizerPrasadEigenspaces is the main procedure.
