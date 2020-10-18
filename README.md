# Pharmacokinetics Modelling and Drug Delivery Research

Pharmacokinetics (PK) is the branch of pharmacology responsible for the study of how different substances interact with living organisms, in particular with the way they are assimilated by said organisms. It provides a quantitative basis for the description of the delivery of a particular drug to a patient, through studying its uptake behaviour and how it diffuses in the body over time.

Any drug can have widely contrasting effects on the body depending on the quantity in which the substance is administered. Too little and the effects will not be visible due mainly to the diffusion of substances that occurs in the body, hence the concentration of the chemical will be too low in the region that it targets. At the same time, too much of the same chemical and adverse effects will be likely to appear. These mainly occur because the large quantity of the drug may not only have an effect on the particular metabolic pathway you wish to treat, but also on several others, producing too strong shifts in them that unbalance the gentle equilibrium in which they find themselves, causing large scale disruptions with observable consequences. 

There are four physiological processes that are quantified in any pharmacokinetic model of a system:
* Adsorption
* Distribution
* Metabolism
* Excretion

Such a model divides the organism into compartments, each corresponding to an organ or system of organs (e.g. blood vessels, muscle tissue) and quantifies the changes in the concentration of the drug in each compartment through a series or ordinary differential equations (ODEs). There is one central compartment through which the drug first enters the body. A number of peripheral compartments, all connected with the central one, but with no interactions present between them, may also be modelled as part of the system. This number can range from zero to many and depends on the type of treatment, i.e. which organs or system of organs it will engage until the active substance reaches its target area.

Each such model is uniquely characterised by parameters entirely dependent on the nature of the average patient and/or of the medication scheme, resulting in three factors that affect the behaviour of the drug:
* Experiment constants:
** Type of dosing: intravenous vs subcutaneous - it affects the number of compartments we need to consider for an accurate representation of the phenomenon
** Dosing protocol: rate at which the drug enters the system - the main fine tuning mechanism we would use to insure optimum efficiency of the treatment and that no adverse effects occur due to overdosing
*  Physiological constants: such as rates of diffusion within compartments, exchange rates between compartments and rate at which drug leaves the body (i.e. Clearance Rate)

Following this methodology proves to be essential in the development of new treatments, to ensure a sufficient quantity of the active substance is administered to the subject for the medicine to be effective.