# LFP-analysis
baseline_index = f >= 2 & f <= 30;
  baseline_power = sum(PXX(baseline_index));
  normalized_delta_power = delta_power / baseline_power;
  normalized_theta_power = theta_power / baseline_power;
  normalized_alpha_power = alpha_power / baseline_power;
  normalized_beta_power = beta_power / baseline_power;
