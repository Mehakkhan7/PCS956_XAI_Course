# Explainable Artificial Intelligence (XAI)

### From Black-Box Models to Interpretable and Transparent AI Systems

**Instructor:** [Mehak Khan](https://www.hvl.no/en/employee/?user=Mehak.Khan)  
**Institution:** [Western Norway University of Applied Sciences (HVL)](https://www.hvl.no/en/), Bergen, Norway  
**Course:** PCS956 Research Trends in Applied Machine Learning  
**Level:** Master’s / PhD  

---

## Course overview

Machine-learning and deep-learning models can achieve strong predictive performance, but their internal behaviour is often difficult to inspect and understand. This raises an important question: **how can we investigate what information a model relies on and how this information contributes to its predictions?**

These questions become especially important in areas such as healthcare, finance, Earth observation, energy systems, autonomous systems, and scientific decision support, where predictive performance alone may not be enough.

This three-week module introduces the foundations and practical methods of **Explainable Artificial Intelligence (XAI)** within **PCS956 Research Trends in Applied Machine Learning** at the Western Norway University of Applied Sciences (HVL).

We will start with the main ideas and terminology behind XAI, including intrinsic and post-hoc explainability, global and local explanations, and model-specific and model-agnostic approaches. We will then apply several explanation methods in Python and examine how their usefulness depends on the model, data modality, and question being asked.

The module also looks critically at the limitations of XAI. An explanation can help us investigate model behaviour, but it does not automatically tell us whether a model is correct, fair, robust, causal, or trustworthy.

The module combines conceptual foundations, Python notebooks, hands-on exercises, discussion, and an individual mini-project.

---

## Learning outcomes

By the end of the module, students should be able to:

- explain why XAI is needed and where it is useful;
- distinguish between **intrinsic** and **post-hoc** explainability;
- distinguish between **global** and **local** explanations;
- understand the difference between **model-specific** and **model-agnostic** methods;
- choose XAI methods that fit the data, model, prediction being explained, and explanation objective;
- apply and interpret XAI methods for different data modalities;
- evaluate explanation quality and stability;
- recognise the assumptions and limitations of XAI methods;
- distinguish explanation from causality, fairness, robustness, and trustworthiness; and
- communicate explanation results clearly and responsibly.

---

## Course plan

| Week | Topic | Description |
|:---:|---|---|
| **1** | **Introduction to Explainable Artificial Intelligence and its taxonomy** | Introduces the motivation for XAI, model understanding in high-impact applications, stakeholders and explanation needs, and key dimensions of the XAI taxonomy. <br><br> **Python notebooks:** Decision Trees and Intrinsic Interpretability, Feature Importance, Intrinsic vs. Post-hoc Explainability, Global vs. Local Explanations. |
| **2** | **Post-hoc XAI methods for machine learning and deep learning** | Introduces commonly used explanation methods and examines how the appropriate approach depends on the model, data modality, and explanation objective. Model-specific and model-agnostic methods are considered together with their practical limitations. <br><br> **Python notebooks:** Coming soon |
| **3** | **Evaluation of explanations and trustworthy AI** | Examines how explanations can be evaluated using functionally grounded, human-grounded, and application-grounded approaches. The week also introduces explanation-quality metrics, sensitivity and perturbation analysis, and the relationship between explainability and trustworthy AI. <br><br> **Python notebooks:** Coming soon |

---

## Mini-project

The module includes an individual XAI mini-project in which you will apply explainability methods to two different data modalities and critically compare the resulting explanations.

Full instructions, requirements, submission details, and assessment criteria are provided in the **Mini-Project 3, Explainable AI** assignment on Canvas.

---

## Important note on interpretation

XAI helps us investigate how a model behaves, but an explanation should not be treated as proof that the model is correct, fair, robust, safe, or trustworthy.

Feature attribution should also not automatically be interpreted as a causal effect.

Explanations are most useful when they are considered together with predictive performance, robustness checks, domain knowledge, and the assumptions of the explanation method.

---

## Prerequisites

Students are expected to have:

- a basic understanding of machine-learning concepts and algorithms;
- familiarity with probability, statistics, and basic linear algebra;
- basic Python programming skills.

Prior experience with deep learning is beneficial but not required.

---

## Python environment

The practical notebooks use standard Python libraries for data analysis, machine learning, deep learning, visualisation, and explainability, including:

- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- SHAP
- PyTorch
- Captum

Depending on the topic, additional libraries may be introduced for specific XAI methods, data modalities, or visualisation tasks.

Students are encouraged to use **Google Colab** or a local Python environment with the required packages installed.

---

## Suggested reading

- Molnar, C. *Interpretable Machine Learning: A Guide for Making Black Box Models Explainable*  
  https://christophm.github.io/interpretable-ml-book/

- Lipton, Z. C. (2018). *The Mythos of Model Interpretability*  
  https://arxiv.org/abs/1606.03490

- Doshi-Velez, F. & Kim, B. (2017). *Towards a Rigorous Science of Interpretable Machine Learning*  
  https://arxiv.org/abs/1702.08608

- Ribeiro, M. T., Singh, S. & Guestrin, C. (2016). *“Why Should I Trust You?”: Explaining the Predictions of Any Classifier*  
  https://arxiv.org/abs/1602.04938

- Lundberg, S. M. & Lee, S.-I. (2017). *A Unified Approach to Interpreting Model Predictions*  
  https://arxiv.org/abs/1705.07874

- Selvaraju, R. R. et al. (2017). *Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization*  
  https://arxiv.org/abs/1610.02391

- Sundararajan, M., Taly, A. & Yan, Q. (2017). *Axiomatic Attribution for Deep Networks*  
  https://arxiv.org/abs/1703.01365

- Adebayo, J. et al. (2018). *Sanity Checks for Saliency Maps*  
  https://arxiv.org/abs/1810.03292

- Rudin, C. (2019). *Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead*  
  https://arxiv.org/abs/1811.10154

Additional readings related to explanation evaluation, robustness, and modality-specific XAI methods will be provided in the relevant weeks.

---

## Course philosophy

Modern AI systems should be evaluated not only by **what they predict**, but also by how they behave, what information they rely on, and whether their use is appropriate for the application.

Explainability gives us tools to investigate these questions, but it does not automatically make a model trustworthy.


> **Prediction tells us what a model predicts. XAI helps us investigate what information the model appears to rely on and how that information relates to its predictions.**
---

## How to cite this course

If you use or adapt material from this course, please cite:

> Khan, M. (2026). *Explainable Artificial Intelligence (XAI): PCS956 Course Module*. Western Norway University of Applied Sciences (HVL).

Repository:
https://github.com
