---
layout: post
title: "What does oesophageal pressure tell you?"
date: 2017-06-30 11:55
category: "Critical Care"
tags: [Ventilation, Physiology]
mathjax: True
---
### Introduction

Oesophageal pressure can be used as a surrogate for pleural pressure. A properly positioned catheter sits close to the pleura as shown in figure 1. Cardiac impulses will also often be seen as an artifact over the oesophageal pressure trace. The presence of a nasogastric tube does not appear to affect oesophageal pressure readings.

Taking oesophageal pressure to be equivalent to pleural pressure allows estimation of transpleural pressure as airway pressure (and by assumption alveolar pressure) is known.

![Figure 1]({{ site.url }}/assets/oesophageal/fig1.svg "Spacial relationship between oesophagus and pleura")

*Figure 1. Spacial relationship between the oesophagus and pleura*

Abbreviation | Quantity
---|---
P<sub>aw</sub> | Airway pressure
P<sub>oes</sub> | Oesophageal pressure
P<sub>pl</sub> | Pleural pressure
P<sub>plat</sub> | Plateau pressure
P<sub>tp</sub> | Transpleural pressure
&Delta;P | Driving pressure

\\[\Large P_{tp} = P_{aw} - P_{pl}\\]

### Transpleural pressure in a passively ventilated patient

In a controlled mode of ventilation, P<sub>oes</sub> can help determine the [optimum level of PEEP](http://www.nejm.org/doi/full/10.1056/NEJMoa0708638#t=article) and prevent excessive applied airways pressures. A high P<sub>tp</sub> means that there is a large pressure gradient across the visceral pleura, potentially leading to alveolar stress, overdistension and ventilator associated lung injury. However if the chest wall is stiff, then a large pressure will be required to overcome this and the transpleural pressure will be small relative to the applied airway pressure. It is not possible to tell from P<sub>aw</sub> alone which situation applies in an individual patient. If P<sub>pl</sub> (ie P<sub>oes</sub>) is known, transpleural pressure can be calculated allowing the two possibilities to be differentiated.

![Figure 2]({{ site.url }}/assets/oesophageal/fig2.svg "Transpleural pressure and chest wall stiffness")
*Figure 2. Transpleural pressure and chest wall stiffness*

Positive end expiratory pressure (PEEP) acts to prevent lung derecruitment, essentially holding open alveoli during expiration. A negative P<sub>tp</sub> (ie when P<sub>pl</sub> > P<sub>aw</sub>) acts in the opposite direction, pressing in on the lung and promoting alveolar collapse. This state is clearly more likely to occur during expiration when P<sub>aw</sub> is lower. A PEEP level such that P<sub>tp</sub> remains positive throughout the respiratory cycle is necessary to minimise derecruitment.

It should be remembered that P<sub>oes</sub> is a surrogate for P<sub>pl</sub> adjacent to the oesophagus. Due to the effects of gravity etc P<sub>pl</sub> may be slightly different elsewhere in the thorax. It may be best to keep the P<sub>tp</sub> calculated from P<sub>oes</sub> a few cmH<sub>2</sub>O above zero to ensure that it remains positive in all regions of the thorax.

![Figure 3]({{ site.url }}/assets/oesophageal/fig3.svg "Transpleural pressure throughout the thorax")
*Figure 3 Transpleural pressure throughout the thorax*

### Transpleural pressure in a spontaneously breathing patient

P<sub>oes</sub> allows easy detection of patient effort in spontaneous breathing. The timing of patient effort relative to delivered airway pressure may be clear, demonstrating subtleties of patient - ventilator synchrony. In figure 4, a fall in P<sub>oes</sub> can be seen in time with the inspiratory increase in P<sub>aw</sub>. Figure 5 shows different forms of asynchrony.

![Figure 4]({{ site.url }}/assets/oesophageal/spont_tp.png "Spontaneous breathing")

*Figure 4 Oesophageal pressure monitoring in a spontaneously breathing patient*

![Figure 5]({{ site.url }}/assets/oesophageal/fig5.svg "Forms of asynchrony")
*Figure 5 Forms of patient - ventilator asynchrony*

Detecting spontaneous (but ineffective, ie not triggering ventilator breaths) effort may be particularly valuable in patients with ARDS on controlled modes of ventilation. Such spontaneous efforts may cause substantial and potentially harmful transpleural pressure gradients and thus [pendelluft](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4217048/) and lung injury.

### Driving pressure

Driving pressure (&Delta;P), defined as the ratio tidal volume (V<sub>T</sub>) to respiratory system compliance (C<sub>RS</sub>), seems to be an [important determinant of mortality in ARDS](http://www.nejm.org/doi/full/10.1056/NEJMsa1410639#t=article).

\\[\Large \Delta P = \frac{V_T}{C_{RS}}\\]

This definition hides the fact that &Delta;P is conceptually the variation in pressure between inspiration and expiration\[1\]. In passively breathing patients, this can be calculated as

\\[\Large \Delta P = P_{plat} - PEEP\\]

ie the plateau pressure minus the PEEP. The concept of &Delta;P applies to both airway and transpleural pressures, ie both &Delta;P<sub>aw</sub> and &Delta;P<sub>tp</sub> can be measured or calculated. In controlled ventilation, P<sub>aw</sub> is the only thing varying between inspiration and expiration so &Delta;P<sub>aw</sub> and &Delta;P<sub>tp</sub> should be very similar. In spontaneous breathing this is not the case as P<sub>pl</sub> will drop below PEEP during inspiration. It is however still possible to read &Delta;P<sub>tp</sub> from the graph of P<sub>tp</sub> against time displayed by the ventilator by looking for the values of P<sub>tp</sub> in expiration and P<sub>plat<sub>tp</sub></sub>.

The majority of research to date has used &Delta;P<sub>aw</sub> but it is likely that &Delta;P<sub>tp</sub> is the more physiologically relevant measure and it makes sense to target this where available. Lower is better and whilst there may not be a true threshold value below which ventilation is "safe", aiming to get &Delta;P<sub>tp</sub> below around 12 - 15 cmH<sub>2</sub>O seems a reasonable strategy.

\[1\] This makes more sense when one remembers that compliance is defined as change in volume with change in pressure and the tidal volume is the change in volume between inspiration and expiration.
