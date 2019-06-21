+++
# Date this page was created.
date = 2018-02-01T00:00:00

# Project title.
title = "THL Android App"

# Project summary to display on homepage.
summary = "Most studies in the field of psychology are conducted with the paper-pencil questionnaire method. Only recently, however, there has been a shift towards online data collection and operationalization via mobile devices. Questions of validity, reliability, and general acceptance have been addressed in several studies and – to date – reveal positive findings for the use of such data collection methods. In addition, questionnaires in digital version allow dynamic adaptations to answers of the interviewee. In this project, I am coordinating the development of the event checklist Threats to Human Life Scale as a smartphone and tablet application with a dynamic output for interviewee’s age. This is a first step towards mapping trauma exposure in remote and insecure regions, as observed in the slums of Rio de Janeiro city, Brazil."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "THLlogo.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["THL Android App"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

**Background**: Research in psychology commonly relies on questionnaires as a way of collecting empirical data on many different topics of human health (Herrmann 1982, Schwarz & Oyserman 2001), such as behavior (Buss & Perry 1992), memory (Hinkin 1998), and cognition (Khawaja & Oei 1992). For this particular purpose, psychologists, clinicians, and researchers use sets of thematic questions printed on paper (questionnaires) to achieve their goal of gathering data. This conventional approach, however, also imposes major difficulties for the completion of psychological surveys.

For example, questionnaires need to be printed and manually filled out, usually generating remarkable amounts of physical material that need to be properly stored. In addition, typos, missing data, or incorrect answers may be produced by the interviewers (Barnette Jr 1950), creating irregular answers that should be first filtered out or corrected by the person responsible for data analysis. Moreover, instructed personnel should conduct interview sessions under controlled sets, such as in a clinic or laboratory, which consumes time and resources of both interviewee and interviewer. In special cases, focal interviewees also need to move from their living places to distant areas where the interview shall take place, increasing financial and logistic costs. Thus, traditional research questionnaires printed on paper may lead to several problems to researchers and their use is limited to particular conditions.

Optimizing data gathering for psychological surveys that rely on paper-pencil questionnaires should therefore be a key issue for many researchers. Nowadays, abundant examples of computer-based online tools might actually help this shift from conventional questions on paper to ‘virtual questionnaires’ (for a list of different static online questionnaires, see the databases in Social Psychology Network and Excel at Life). Computer-based tools have comparatively several advantages over the use of paper-pencil questionnaires. For instance, they allow gathering of more reliable data, provided that answers are set to a particular range or category constraint. Data acquisition and manipulation is faster, considering that answers might be automatically saved, transformed, or exported to analysis, which avoids the time-consuming task of data entry into spreadsheets and the generation of typos. In case different studies are performed using the same virtual questionnaire, answers might also be formatted identically, allowing for better representation, comparison, and reproducibility of the data. Hence, computer-based questionnaires are potential alternatives for improving psychological surveys.

Despite criticism, online surveys have been well regarded as reliable and valid sources of study data. For example, Ramo et al (2011) gathered self-reports for smoking behavior on a small study group of 248 young adults, and they found that smoking quantity was comparable to the national levels produced after household interviews in USA. Moreover, Gosling et al (2004) suggested that online surveys consistently produced results similar to those of traditional methods on a sample of over 360,000 online web visitors. There are several studies that further support the reliability of online data, such as for the construct of reaction-time (McGraw et al 2000), self-esteem (Robins et al 2002), and self-monitoring (Buchanan & Smith 1999). Additionally, online surveys may also produce data with good quality. For example, Hewson (2016) observed that several studies have already been replicated and cross-validated with conventional methods, showing that online surveys produce representative valid data on psychometric traits. Therefore, although common sense should expect that participants of an online survey might not be authentic or give honest answers (due to lack of close control and monitoring), in reality online surveys are reliable instruments for gathering research data.

Of course, the use of online surveys is an ideal alternative for focal study groups that constantly have access to computers permanently connected to the internet. In poor, remote, or even dangerous areas, however, people generally do not have computers at hand. Thus, in these cases, further alternatives need to be offered for researchers to conduct their investigations. Thanks to technology, cheap smartphones now practically allow everyone to get internet access. This is especially true for Africa and parts of South America, where even money transfers and payments can be largely done by phones (Etzo & Collender 2010; Donner 2008). Software applications that are implemented as surveys in tablets or smartphones are relatively scarce in comparison to static online questionnaires nevertheless (e.g., Lindhiem et al 2015; Schickler et al 2017; Schobel et al 2017). In cases where research is carried out in critical areas, the use of smartphones might be much more feasible than the use of computers. Therefore, using portable devices might be an optimal alternative to conduct psychological surveys in certain conditions. Moreover, the implementation of questionnaires to assess different human traits are not widely spread, such survey versions still need to be translated and implemented into software applications, especially those that fit the above mentioned working conditions.

**Focal working questionnaire**: Threats to Human Life (THL) Scale

The Threats to Human Life (THL) Scale was created by researchers of the University of Konstanz (Köbach, Elbert & Schauer, in prep), and it is an instrument to retrospectively assess the social and physical threats to a person’s life as well as dominance behaviour. It takes into account essential attributes for an organism survival, e.g. oxygen, water and glucose supply, tissue and organ integrity, social inclusion, and bonds. For each life event described by the instrument, the THL also requires the specific participant’s age, together with information on the actor of violence and the regularity of the event in case (for details, see Figure 1 on next page).

The THL can be applied in research and therapy to gain profound understanding of an individual’s history of trauma and aggression. However, given that event assessment depends on age, this instrument also generates a large amount of outcome variables that need to be efficiently dealt with later on. It is crucial that respondents have clear instructions before filling out the questionnaire, but it is still common to observe missing values and discordant answers. Furthermore, the answers have to be brought into an ordered format from which data can be correctly analysed and linked to trauma-related disorders, (epi)genetic modifications, and/or social variables. If these steps are obeyed, a larger validation study may build the basis for the THL to become a more commonly used instrument for the assessment of trauma in various settings. The THL may further serve as a risk evaluation tool for trauma-related disorders where appropriate services can be suggested to
those who seek help.

So far, the THL has been piloted in Armenia (Master’s degree project by Tamara Stepanyan) and as an online self-report questionnaire in Germany (Master’s degree project by Valentina Diegel and Florina Willand). In the latter, a UniPark/Questback was used with appropriate codes to account for the dynamic effect of age. In general, feasibility and validation questions were positive, with participants reporting a high variation of events. Additionally, one long-term study in DR Congo is currently ongoing.

The development of a portable computer-based (i.e. in smartphone or tablet) version of the THL would allow not only an optimization of the data control and acquisition, but also large validation studies to take place. This is especially true given the dynamic nature of the THL data output (dependant on age of participants), but also because of the considerable amount of data generated that needs to be processed. Moreover, a THL application for portable devices could allow a study to be conducted without interviewers, in which the data could be automatically sent over to a safe storage server. This is particularly interesting for study sets where the fieldwork is conducted distant from the location of the data analysis, especially in insecure settings.

**Planed timeline**: The development of the application is planned to take place in 2018. A pilot test will be conducted in Konstanz for approximately one month with subsequent data output analysis. A second pilot will be implemented in a project in Rio de Janeiro city, Brazil, during a one-week stay in November 2018.

**Scientific aim**: Produce and pilot the THL as a software application for mobile devices. After proof of concept, I will be able to further write a project proposal (e.g. to the Deutsch Forschungsgemeinschaft) for a validation study of the THL as a technically supported self-report instrument.
