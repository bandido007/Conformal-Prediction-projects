🎯 A collection of practical implementations for uncertainty quantification in machine learning using conformal prediction methods.
About
This repository hosts implementations of conformal prediction techniques, focusing on real-world applications. It currently features an Enhanced RAPS (Regularized Adaptive Prediction Sets) implementation for medical diagnostics, demonstrating how to:

Provide reliable uncertainty estimates
Generate prediction sets with guaranteed coverage
Adapt to domain-specific needs (e.g., medical diagnostics)
Balance accuracy with informative predictions

Perfect for:

- 🔬 Researchers working with uncertainty quantification
- 💻 Data scientists implementing reliable ML systems
- 🏥 Healthcare professionals exploring ML reliability
- 📚 Students learning about conformal prediction

Projects

1 . **Enhanced RAPS Medical**

A specialized implementation of Regularized Adaptive Prediction Sets (RAPS) for medical diagnostics, focusing on reliable uncertainty quantification in clinical predictions.

Overview
EnhancedRAPSMedical combines conformal prediction with medical-specific enhancements to provide:

   -  Reliable uncertainty estimates for medical predictions
   - Guaranteed error rate control
   - Adaptive prediction set sizes
   - Medical-specific confidence assessments

Features

  - 🏥 Medical-Specific Design: Tailored thresholds and interpretations for clinical use
  - 🎯 Uncertainty Quantification: Clear confidence levels and assessment labels
  - 📊 Conformal Prediction: Statistically valid prediction sets
  - 🔄 Adaptive Behavior: Flexible prediction set sizes based on confidence
  - 📈 Comprehensive Metrics: Including age-stratified coverage analysis

Use Cases

  Diagnostic Support
  
  - Binary medical classifications
  - Risk assessment
  - Screening applications


Clinical Decision Support

  - Confidence-based recommendations
  - Uncertainty-aware diagnostics
  - Risk stratification



Model Behavior
The model provides three levels of assessment:

  - Definitive: High confidence predictions
  - Uncertain: Moderate confidence, may include alternative predictions
  - Highly Uncertain: Low confidence, includes multiple possible outcomes

Performance Metrics
The implementation tracks several key metrics:

  - Average coverage
  - Set size efficiency
  - Error rates
  - Age-stratified coverage (when age data is available)

Requirements

  - Python 3.7+
  - NumPy
  - Pandas
  - Scikit-learn compatible base model
