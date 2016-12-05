# Foundations in Scientific Computing

**A five-day, intensive, hands-on workshop on the foundational skills that everyone using computers in the pursuit of scientific research should have.**

*Offered for the first time 2–6 January 2017, at Universidad Técnica Federico Santa María, Valparaíso, Chile.*

---

Every student today (graduate or undergraduate) is using computers on a daily basis.
But to be proficient with computers as a tool for science, you need professional-grade skills.
This workshop teaches the computing skills that we—as a research group in computational science and engineering—think everyone should have.

In recent years, the concern for reproducibility in computational science has gained traction.
Our research group has been pushing for several years the adoption of better standards for reproducible research.
These standards include treating scientific software as a core intellectual product, adding automation to our data handling and analysis, and the open sharing of our digital objects.

This course provides an introduction to the tools and techniques that we consider fundamental for responsible use of computers in scientific research. They include the following:

1. command line utilities in Unix/Linux 
2. an open-source scientific software ecosystem (our favorite is Python's)
3. software version control (we advocate the distributed kind: our favorite is git)
4. good practices for scientific software development: code hygiene and testing
5. knowledge of licensing options for sharing software 

## Reproducible Computational Research

The weeklong workshop also includes a presentation and discussion of the ["Barba-group Reproducibility Syllabus"](https://hackernoon.com/barba-group-reproducibility-syllabus-e3757ee635cf#.wn9brj30m)—an annotated bibliography of our Top-10 readings on the topic of reproducibility.
Number 7 in the list of readings is an article titled "Ten simple rules for reproducible research" (Sandve et al., 2013).
Two unifying ideas run through the "ten simple rules":
(1) that automation is a key device for reproducibility, and
(2) that version control is the core technology for dealing with software as a living, changing thing.
These ideas justify insisting that _command-line skills are a must._

The skeleton for our practice of reproducible research is the pledge ["Reproducibility PI Manifesto"](http://lorenabarba.com/gallery/reproducibility-pi-manifesto/) (2012).
It consists of a commitment to:
(1) teach group members about reproducibility; 
(2) keep all code and writing under version-control; 
(3) complete code verification and validation, and publish openly the results; 
(4) for main results in a publication, share data, plotting scripts, and figures under CC-BY; 
(5) upload preprints to [arXiv](https://arxiv.org) at the time of submission of a paper; 
(6) release code no later than the time of submission of a paper; 
(7) add a "Reproducibility" statement to each publication; 
(8) keep an up-to-date web presence.

With this workshop, we propel the first commitment beyond our research group: 
we take responsibility for not only teaching our group members, but broadly disseminating the know-how to our community. 
The second commitment helps for what University of Washington professor Randall LeVeque<sup>1</sup> called _"private reproducibility"_: 
we can rebuild our own past research results from the precise version of the code that was used to create them.
Private reproducibility also demands fully automating the analysis and visualization of data.
Stanford professor Jon Claerbout said:
“I’ve learned that interactive programs are slavery (unless they include the ability to arrive in any previous state by means of a script).”
With this in mind, two technologies are enemies of reproducible research:
GUI-based image manipulation, and spreadsheets.
Figures that visualize data, or image processing applied to photographs, can only be reproducible if made with scripts.
And spreadsheets impair reproducibility because they conflate input, output and code (as noted by Berkeley professor Philip Stark).
This situation calls for adopting a scientific software stack for programmatic analysis and visualization.
Our favorite environment to accomplish this is Scientific Python.

Genuine reproducible research is not only privately reproducible, but publicly so.
That's why all our subsequent reproducibility commitments deal with open access to data, code and publications.

### Definitions

**Reproducible research:**  Authors provide all the necessary data and the computer codes to run the analysis again, re-creating the results.

**Replication:** Arriving at the same scientific findings as another study, collecting new data (possibly with different methods) and completing new analyses. A full replication study is sometimes impossible to do, but reproducible research is only limited by the time and effort we are willing to invest.

## References

<sup>1</sup> LeVeque, Randall J. (2012), "Issues in Reproducibility," talk given at the ICERM Workshop on Reproducibility in Computational and Experimental Mathematics, Brown University [slides PDF](https://icerm.brown.edu/materials/Slides/tw-12-5/Issues_in_Reproducibility_]_Randy_LeVeque,_University_of_Washington.pdf)
