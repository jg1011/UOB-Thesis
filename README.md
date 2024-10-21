# To-Do

### Penrose's Red Book

### Penrose's Blue Book
- Exercise 2.2 :(
- Type up proofs in chapter 3, getting good w/ Mecke's is mandatory. 

### Pach & Agarwal's Combinatorial Geometry
All Todos are on CH7, the chapter of primary interest to me
- Figure out that one line of magic in Davenport & Roger's result, ask Penrose? 
- Learn Hlawka's theorem proof (already read once but go beyond surface)
- Make jump to Minkowski-Hlawka theorem 

It is worth noting this chapter takes a lattice approach to sphere packing, something likely to not 
be optimal (or at least probably not beat Campos2023) but is of independent interest. 

### Campos 2023
Campos & Co approach bounding sphere packing densities in high dimensional space with random geometric graphs & a new bound on the maximal independent set of a (fixed) graph. The first 3 steps in the methodology (of the proof of thm 1.1) were quite literally exactly what I had in mind. The advent of theorem 1.3 to bound the large independent set was creative, and I believe this proof, while being left temporarily, is of independent interest. 

The methodology is as follows: 
- Consider a PPP with carefully chosen intensity (one that will work nicely with our other results)
- Remove points of high degree / codegree 
- Bound the independent set of the geometric graph left over (where the radius is just double the radius of the unit-volume $d$-sphere)

It is worth mentioning I had the idea for this methodology (modulo of course some technicalities, my uniformity conditions were simply just removing high degree points but I would've adapted these to whatever independent set theorem used, as in Campos2023) in my back garden approx 30 minutes before finding this paper. In the words of my housemate, some strong back of the cigarrete carton mathematics. Never in a million years would I have (unless the proof is easier than it looks) come up with theorem 1.3 and thus nor would I have chosen their uniformity conditions. I imagine there's other approaches possible, while their independent set bound is tight it is worth investigating the size of an independent set with different regularity conditions. I can imagine 
this technique having non-trivial yeild in other tangential areas in combinatorial geometry, for example their paper provides a seemingly trivial adaptation of their techniques to provide a new bound on the spherical codes 
problem as well. PITCH THIS TO PENROSE. 

Various TO-DOs:
- Understand sharpness argument for theorem 1.3, seen in the 2nd paragraph page 4. 
- Prove the univariate Mecke, either directly or as a special case of Penrose (blue book) Mecke. 
- Improve your Poisson tail bound and ideally arive at their bound. Note on this in pdf
- Verify $t = \Delta^{-1/3} - \Delta^{-1}$ algebra bash. $\Delta(t+1) = \Delta(1+\Delta^{-1/3}) - 1$ to be applied to RHS of $(\dagger)$ is fine, just the bound.
- Finish bounding of rightmost term in sum (lemma 2.30) $\mathbb{E}|\{y \in X \setminus B_x(\log d) : I_{x,y} \geq \eta \Delta - 1\}|$
- Look into remarks 2.31, 2.32 & 2.33
- Finish proof of lemma 3.2 in Campos2023 (almost done)

Notes are currently up to (but not including) the proof of theorem 1.3. I'd like to understand this tool, particularly on the relevance of random graph theory vs just graph theory. R\"{o}dl nibble is cool ass idea. 

### Misc
- Fix claimcount numbering and devise a better system for the remaining counts


