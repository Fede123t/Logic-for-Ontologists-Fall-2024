SUB-PROPERTY PERMUTATIONS:

Axiom: for [B] object_subProperty of [A], any {x,y} pair of instances in B will occur in [A].
However, it is not the case that any {x,y} in A will occur in [B].
So, the issue is to find where the logical conditions of Sub_Property [B] violate those of their parent object_property [A]. 

For any Object Property [A] as (Functional, Inverse Functional, Transitive, Symmetric, Asymmetric, Reflexive, Irreflexive),
Consider whether its sub_Property [B] violates what is maintained by the logical committments of [A].
Cases are considered in piecemeal fashion examining all possible combinations of some [A] paired with each possible [B].
Permutation involving inverses of [A] & [B] (A', B' respectively) are forthcoming. 

1. [A] as Functional
        
        [A] + [B] as Functional 
        The functional properties of [B] do NOT violate the functional properties of [A].

        [A] + [B] as Inverse Functional 
        The inverse functional properties of [B] do NOT violate the functional properties of [A].

        [A] + [B] as Reflexive
        The reflexive properties of [B] do NOT violate the functional properties of [A].

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] do NOT violate the functional propertis of [A].

        [A] + [B] as Symmeytric
        The symmetric properties of [B] do NOT violate the functional properties of [A].

        [A] + [B] as Asymmetric 
        The asymmetric properties of [B] do NOT violate the functional properties of [A].

        [A] + [B] as Transitive
        The transitive properties of [B] DO violate the functional properties of [A].
            PROOF: 
                -Functionality holds that for object property <R>, {x} can be related to more than one distinct individual {y}.
                -Transitivity holds that if xRy and yRz then xRz. 
                -It follows that the functional cardinality of [A] is violated by transitivity in [B].


2. [A] as Inverse-Functional

        [A] + [B] as Functional 
        The functional properties of [B] do NOT violate the inverse-functional properties of [A].

        [A] + [B] as Inverse-Functional
        The inverse-functional properties of [B] do NOT violate the inverse-functional properties of [A].

        [A] + [B] as Reflexive
        The reflexive properties of [B] do NOt violate the inverse-functional properties of [A].

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] do NOT violate the inverse-functional properties of [A].

        [A] + [B] as Symmetrical
        The symmetrical properties of [B] do NOT violate the inverse-functional properties of [A].

        [A] + [B] as Asymmetrical
        The asymmretical properties of [B] do NOT violate the inverse-functional properties of [A].

        [A] + [B] as Transitive 
        The transitive properties of [B] DO violate the inverse functional properties of [A].
            PROOF:
                -For xRy where R is inverse-functional, only some {x} can relate to {y} by R.
                -By transitivity if xRy and zRx where R is the same object property then zRy follows.
                -However, this would entail that both {x} and {z} are uniquely connected to {y} by object property R thus producing an inconsistency. 



3. [A] as Symmetrical 

        [A] + [B] as Functional
        The functional properties of [B] do NOT violate the symmetrical properties of [A].

        [A] + [B] as Inverse-functional
        The inverse-functional properties of [B] do NOT violate the symmetrical properties of [A].

        [A] + [B] as Reflexive
        The reflexive properties of [B] do NOT violate the symmetrical properties of [A].

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] do NOT violate the symmetrical properties of [A].

        [A] + [B] as Asymmetrical
        The asymmetrical properties of [B] DO violate the symmetrical properties of [A].
            PROOF: 
                -By symmetry, if xRy then yRx
                -Asymmetry holds that if xRy then ~yRx
                -Some xRy and ~yRx cannot hold simulataneously. 

        [A] + [B] as Symmetrical
        The symmetrical properties of [B] do NOT violate the symmetrical properties of [A].

        [A] + [B] as Transitiive
        The transitive properties of [B] do NOT violate the symmetrical properties of [A].

    

4. [A] as Asymmetric

        [A] + [B] as Functional
        The functional properties of [B] do NOT violate the asymmetrical properties of [A].

        [A] + [B] as Inverse-Functional
        The inverse-functional properties of [B] do NOT violate the asymmetrical properties of [A]. 

        [A] + [B] as Reflexive
        The reflexive properties of [B] DO violate the asymmetric properties of [A].
            PROOF:
                -By asymmetry, if xRy then ~(yRx)
                -Reflexivity holds that xRx
                -If xRx then ~(xRx)
                -xRx mirrors its negations which violates asymmetry.

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] do not violate the asymmtrical  properties of [A].

        [A] + [B] as Symmetrical
        The symmetrical properties of [B] DO violate the asymmetyrical properties of [A].
            PROOF:
                -By asymmetry, if xRy then ~(yRx)
                -By symmetry, if xRy then yRx
                -yRx ^ ~(yRx) cannot hold simulataneously.

        [A] + [B] as Asymmetrical
        The asymmetrical properties of [B] do NOT violate the asymmetrical properties of [A].


        [A] + [B] as Transititve
        The transitive properties of [B] DO violate the asymmetrical properties of [A].
            PROOF: 
            -Suppose xRy
            -By asymmetry, ~(yRx)
            -Suppose yRz, zRx
            -By transitivity, yRx
            -yRx ^ ~(yRx) is a direct contradiction. 



5. [A] as Reflexive 

        [A] + [B] as Functional
        The functional properties of [B] do NOT violate the reflexive properties of [A].

        [A] + [B] as Inverse-Functional
        The inverse-functional properties of [B] do NOT violate the reflexive properties of [A].

        [A] + [B] as Reflexive
        The reflexive properties of [B] do NOT violate the reflexive properties of [A].

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] DO violate the reflexive properties of [A].
        PROOF:
            -By reflexivity, for any instance {x} and object_property (R), xRx.
            -By irreflexivity, {x} cannot relate to itself... ~(xRx)
            -xRx and ~(xRx) cannot hold at once. 

        [A] + [B] as Symmetrical
        The symmetrical properties of [B] do NOT violate the reflexive properties of [A].

        [A] + [B] as Asymmetrical
        The asymmetrical properties of [B] DO violate the reflexive properties of [A]
        PROOF:
            -By reflexivity, xRx
            -By asymmetry, if xRy --> ~(yRx)
            -xRx is necessarily symmetrical to itself, xRx
            -xRx ^ ~(xRx) cannot hold simulataneously.

        [A] + [B] as Transitive
        The transitive properties of [B] do NOT violate the reflexive properties of [A].



6. [A] as Irreflexive

        [A] + [B] as Functional
        The functional properties of [B] do NOT violate the irreflexive properties of [A]. 

        [A] + [B] as Inverse-Functional
        The inverse-functional properties of [B] do NOT violate the irreflexive properties of [A]. 

        [A] + [B] as Reflexive
        The reflexive properties of [A] DO violate the irreflexive properties of [A].
        PROOF: (see section 5. lines 151-154)

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] do NOT violate the irreflexive properties of [A].

        [A] + [B] as Symmetrical
        The symmetrical properties of [B] DO violate the irreflexive properties of [A].
        PROOF: 
            -Some symmetrical expressions are reflexive.
            -Ex: xRx is reflexive and symmetrical to itself.
            -By irreflexivity, ~(xRx)
            -In this case, a contradiction arises. 
        
        [A] + [B] as Asymmetrical
        The asymmetrical properties of [B] do NOT violate the irreflexive properties of [A].

        [A] + [B] as Transitive
        The transitive properties of [B] DO violate the irreflexive properties of [A].
        PROOF: 
            -Consider xRy, yRz
            -By transitive xRz
            -Consider zRx
            -By transitive xRx
            -By irrefelxive ~(xRx)
            -Contradiction



7. [A] as Transitive

        [A] + [B] as Functional 
        The functional properties of [B] DO violate the transitive properties of [A].
        PROOF: (see section 1. lines 33-37)

        [A] + [B] as Inverse-Functional
        The inverse-functional properties of [B] DO violate transitive properties of [A].
        PROOF: (see section 2. lines 61-64)

        [A] + [B] as Reflexive
        The reflexive properties of [B] do NOT violate the transitive properties of [A].

        [A] + [B] as Irreflexive
        The irreflexive properties of [B] DO violate the transitive properties of [A]. 
        PROOF:
            -Some transitive operations become reflexive.
            -See pt.6 lines 202-207
        [A] + [B] as Symmetrical
        The symmetrical properties of [B] do NOT violate the transitive properties of [A].

        [A] + [B] as Asymmetrical
        The asymmetrical properties of [B] DO violate the transitive properties of [A]. 
        PROOF:
            -See lines 131-135

        [A] + [B] as Transitive
        The transitive properties of [B] do NOT violate the transitive properties of [A].


        


