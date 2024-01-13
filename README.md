# <a href=https://arxiv.org/abs/2304.10755>Interpretable and Robust AI in EEG Systems: A Survey</a>




This is a repository maintain an ever-evolving list of papers on the interpretability and robustness of AI in EEG systems, with frequent updates to ensure its comprehensiveness
and timeliness.


## The contribution of this survey
1. This is the first comprehensive survey focusingon the interpretability and robustness of AI in EEG systems.
2. We propose a novel taxonomy of interpretability and robustness for EEG systems.
3. We summarize and highlight the emerging and most representative interpretable and robust AI works related to EEG systems.
4. We discuss some open problems and promising directions for future EEG systems.

## Summary of Interpretable AI in EEG Systems
| **Interpretability Categories** | **Methods** | **Coverage** | **Explanation Type** |
|---------------------------------|-------------|--------------|----------------------|
| *Backpropagation-based Methods* | LRP         | Local/Global | Attribution          |
|                                 | DeepLIFT    | Local/Global | Attribution          |
|                                 | CAM         | Local        | Attribution          |
|                                 | Grad-CAM    | Local        | Attribution          |
| *Perturbation-based Methods*    | LIME        | Local        | Attribution          |
|                                 | SHAP        | Local        | Attribution          |
| *Rule-based Methods*            | Random Forest          | Global       | Decision Rules       |
|                                 | Fuzzy Inference Systems         | Global       | Fuzzy Rules          |
|                                 | Bayesian Systems          | Global       | Bayesian Rules       |



## Comparison of different interpretanility methods in EEG Systems
|                                  | **Backpropagation-based Method**                                                                 | **Perturbation-based Method**                                                  | **Rule-based Method**                                                             |
|----------------------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| **Mechanism**                    | Analyze the feature contribution by backpropagating the gradients from predictions.             | Explain the original model's behavior with local surrogate models.            | Explain model using specific logic rules                                         |
| **Explanation Stage**            | Post-hoc                                                                                         | Post-hoc                                                                       | Ante-hoc                                                                          |
| **Model Dependence**             | Model-specific                                                                                   | Model-agnostic                                                                 | Model-agnostic                                                                    |
| **Flexibility**                  | Low                                                                                              | High                                                                           | High                                                                              |
| **Application Scenario**         | Differentiable models                                                                            | Tolerable of high computational costs                                          | Availability of priori knowledge                                                  |
| **Limitation**                   | Gradient dependency; Narrow applicability                                                        | Computationally intensive; Prone to overfitting                                | Oversimplify complex EEG systems; Require domain expertise                        |


## Summary of Robust AI in EEG Systems