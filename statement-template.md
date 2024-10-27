# Statement Template

> [!NOTE]
> This template treats the statement as a singular entity, combining the statement of
> purpose and personal statement. For institutions that require these statements to be
> separate, the contents of this template will need to be modified somewhat.

## Statement

Modern neuroscience is entering an era of unparalleled amounts of data through the
continuous improvement of experimental tools and techniques[^1]. This increase in the
size of datasets presents exciting opportunities to better understand the brain but
comes at the cost of increased complexity. This increase in the complexity of data has
resulted in the field of neuroscience shift towards the direction of computationally
intensive analytical methods. Motivated by my exposure to neuroscience through
independent research projects and advanced coursework, I am interested in working at the
intersection of experimental, computational, and theoretical neuroscience to answer two
questions:

1. What are the organizational principles of sensory systems[^2]?
2. How do sensory systems translate input into observable behaviors?

Below, I detail how my previous experiences have prepared me to be successful in
graduate school and why your institution is the right choice for me to pursue my PhD.

> [!NOTE]
> I'm not sure if I should explicitly name the institution at this point, or wait until
> the final section of this statement to do so.

[^1]:
    For instance, the field of magnetic resonance imaging (MRI) research has
    experienced a steady increase in the temporal and spatial resolution with the
    improvement of the field strength of MRI scanners and refinement of coils used in
    recording data.

[^2]:
    By sensory systems, I explicitly mean those systems that allow an organism to
    interact with their environment.

### Preparedness

My path to neuroscience research was not straightforward. Entering Brandeis University,
I intended on becoming a physician. It was not until my senior year, while working on my
senior thesis, that I realized my passion for research. Because of this, I left Brandeis
with less experience than I had hoped for. Thus, it has been my mission at the National
Eye Institute (NEI) to not only perform exceptional research, but to bolster my
presentation, teaching, and outreach experience as well.

My first substantial research experience came during my sophomore year at Brandeis
after joining the laboratory of Dr. Stephen Van Hooser. The focus of our work at the
time was to better understand the development of the mammalian visual cortex using
optical and optogenetic techniques. We studied the development of neurons in the primary
visual cortex (V1), with a specific focus on tuning properties, in ferrets.

I, along with Dr. Van Hooser and a graduate student, investigated whether neurons in V1
of ferrets possessed characteristics consistent with tuning for speed: the ratio of
temporal frequency (TF) to spatial frequency (SF). The overarching goal of the project
was to better understand motion processing in the visual cortex, which has historically
been less understood than spatial processing. Motivated by data recorded in the cat,
primate, rodent, and ferret visual cortex suggesting some level of interaction between a
variety of tuning properties, we sought to investigate the co-tuning of direction
selectivity, TF, SF, and speed. My research project, which later became my senior
thesis, focused on assessing whether neurons in ferret V1 were tuned for speed, a tuning
property thought to arise in higher-order visual areas (HVAs).

I developed an algorithm for fitting previously described two-dimensional Gaussian
model[^3] to the firing rate of neurons recorded at various depths in V1 in anesthetized
ferrets in a stereotaxic rig. This algorithm was integral to the project as it provided
us with the parameter we used to assess whether a neuron was tuned for speed: the speed
index. I further enhanced the algorithm by implementing an _F_-test to determine whether
including the speed index resulted in a significantly better fit. The addition of this
statistical test allowed us to determine whether a neuron exhibited significant tuning
for speed, that is, a high speed index value was not the result of an edge case for the
fitting algorithm[^4]. We found that approximately one quarter of neurons in V1
exhibited significant tuning for speed, one quarter did not possess any properties
consistent with speed tuning, and the remaining set of neurons had tuning properties
existing somewhere in between. This finding implies that properties previously believed
to arise in HVAs could in part be inherited from V1, further elucidating the roles of
these visual areas in perception.

I had to construct to code in such a way as to prevent fits from ending up in local
error minima and developed visualization techniques to ensure that the algorithm was
robust. I learned how important it is to carefully monitor the progression of data
through a pipeline to ensure that the process is producing quality output.

After graduating from Brandeis University with a bachelor's degree in neuroscience and
biology and a minor in philosophy, I was fortunate enough to receive a postbaccalaureate
Intramural Research Training Award (IRTA) to conduct research as part of the (NEI) full
time. I joined the laboratory of Dr. Bevil Conway in the Laboratory of Sensorimotor
Research (LSR), where we study the pathways and computations involved in the
transformation of sensory input to observable behavior with a particular focus on the
visual system. At the LSR, I have the privilege of working in a tight knit,
collaborative group.

My first research project sought to better understand the mechanisms underlying the
long-term association between color and shape, an association providing the backbone for
object concepts[^5], a hallmark of intelligence. I worked with two fellow
postbaccalaureate researchers and a graduate student to investigate these mechanisms in
two juvenile non-human primates (NHPs) using functional MRI (fMRI). I assisted with
experiments, analysis, and the development of tools and methods that improved the
performance of the neural decoding model we utilized to assess where in the brain these
color-shape associations occur. I presented my work at the NIH during the annual
[postbaccalaureate poster day](https://www.training.nih.gov/me/ppd/). This project
provided me with invaluable experience working with NHPs in a research environment and
laid the foundation for me to embark on my current research project.

Under the guidance of a postdoctoral researcher and Dr. Conway, I currently lead a
project seeking to better understand the function roles of cortical visual areas in
humans with fMRI. The project is focused on retinotopically-defined visual cortex, that
is, the collection of visual areas possessing some neural representation of the visual
information projected onto the retina. The functional roles that these visual areas play
in the processing of visual information is not well understood. We utilize a set of
drifting grating stimuli parametrically varying in hue, saturation, and SF to ascertain
the functional signatures of retinotopically-defined cortex. The main analysis method is
a machine learning model that maximizes the variance between and minimizes the variance
within distinct visual areas. The result of which is an array detailing the relative
contributions of the stimulus features to the functional activity for a given region.

In advancing this project, I [developed](https://github.com/nlaskyni/ccsf) the
experimental design, analysis pipeline, stimuli, and refined the analytical model. I am
responsible for recruiting participants and calibrating the stimulus presentation
apparatus. I consulted with scientists across the NIH to determine whether my choice of
experimental design and processing steps would lead to robust, reproducible results. I
was able to give a presentation on this project at the NIH through the postbaccalaureate
seminar series.

[^3]:
    This text is a placeholder; the citation for the paper that introduced the model
    will be put here.

[^4]:
    For instance, while developing the fitting algorithm, we noticed that a subset of
    neurons possessed large speed index values but exhibiting tuning preferences at the
    edge of recorded stimulus configurations.

[^5]:
    An example being a banana, which can be reduced to a yellow crescent with respect to
    color and shape.

### Career goals

In the future, I hope to serve on the faculty of an academic institution. I owe this to
the mentorship of Dr. Van Hooser and Dr. Conway, who have both influenced me as a
researcher, scientist, and person. My experience at Brandeis and the NIH has reinforced
my desire to not only conduct research, but to teach and be a part of the community at
my institution and beyond. I have been fortunate enough to teach research fellows and
undergraduate students at the NIH, the latter of which resulted in an NEI Director's
Award. I led two journal clubs, presenting papers outside my immediate field to the
entire LSR. I am involved in councils at the branch and institute level, organizing and
moderating events and conferences and improving the experience of fellows and
investigators alike.

> [!NOTE]
> It is at this point that the statement will need to be tailored to individual
> institutions.
