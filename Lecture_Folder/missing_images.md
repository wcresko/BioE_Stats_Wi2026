# Missing Image Files

Image files referenced in lecture .qmd files but not found in the `images/` directory.

**Total: 45 missing images across 6 lecture files**

---

## Week1.qmd (1 missing)

| Missing Filename | Notes |
|---|---|
| `your_image.png` | Placeholder/template reference (lines 1223, 1229) -- likely intentional |

## Week3.qmd (1 missing)

| Missing Filename | Possible existing match |
|---|---|
| `week09_18_baron_munchausen_bootstrap.jpeg` | `week09_18_slide030.jpeg` may be the intended file |

## Week6.qmd (1 missing)

| Missing Filename | Possible existing match |
|---|---|
| `week06_18_anova_table_treatment_groups.jpeg` | `week06_18_section5b_slide017.jpeg` may be the intended file |

## Week7.qmd (30 missing)

### Legacy "images_5" series (no matches found)

| Missing Filename |
|---|
| `images_5a.006.jpeg` |
| `images_5b.001.jpeg` |
| `images_5b.005.jpeg` |
| `images_5b.006.jpeg` |
| `images_5b.007.jpeg` |
| `images_5b.009.jpeg` |
| `images_5b.010.jpeg` |
| `images_5b.012.jpeg` |

### week07 series (existing slide-numbered files may be the correct content)

| Missing Filename | Possible existing match |
|---|---|
| `week07_01_walking_stick_insect_femur.jpeg` | `week07_01_section7a_slide001.jpeg` |
| `week07_02_walking_stick_femur_length_variation.jpeg` | `week07_02_section7a_slide002.jpeg` |
| `week07_03_nested_design_within_individuals.jpeg` | `week07_03_section7a_slide003.jpeg` |
| `week07_04_nested_anova_table_insects.jpeg` | `week07_04_section7a_slide004.jpeg` |
| `week07_05_nested_design_hierarchy_diagram.jpeg` | `week07_05_section7a_slide005.jpeg` |
| `week07_06_nested_model_equations_one_two_levels.jpeg` | `week07_06_section7a_slide006.jpeg` |
| `week07_09_nested_anova_table_formulas.jpeg` | `week07_09_section7a_slide008.jpeg` |
| `week07_10_nested_anova_r_syntax_table.jpeg` | `week07_10_section7a_slide009.jpeg` |
| `week07_11_sea_urchin_algae_experiment_design.jpeg` | `week07_11_section7a_slide010.jpeg` |
| `week07_12_tadpole_photograph.jpeg` | `week07_12_section7a_slide011.jpeg` |
| `week07_13_pesticide_predator_survival_interaction.jpeg` | `week07_13_section7a_slide012.jpeg` |
| `week07_14_factorial_anova_interaction_formula.jpeg` | `week07_14_section7a_slide013.jpeg` |
| `week07_18_interaction_plots_fertilizer_temperature.jpeg` | `week07_18_section7a_slide022.jpeg` |
| `week07_19_factorial_anova_null_hypotheses_fixed.jpeg` | `week07_19_section7a_slide017.jpeg` |
| `week07_20_factorial_anova_null_hypotheses_random.jpeg` | `week07_20_section7a_slide018.jpeg` |
| `week07_21_two_factor_crossed_anova_table.jpeg` | `week07_21_section7a_slide019.jpeg` |
| `week07_22_f_ratio_table_fixed_random_factors.jpeg` | `week07_22_section7a_slide020.jpeg` |
| `week07_23_factorial_model_significant_terms.jpeg` | `week07_23_section7a_slide021.jpeg` |

### week10 ANCOVA series (referenced from Week7.qmd)

| Missing Filename | Possible existing match |
|---|---|
| `week10_11_neanderthal_human_brain_size.jpeg` | `week10_11_section7b_slide005.jpeg` |
| `week10_12_neanderthal_human_skulls_skeletons.jpeg` | `week10_12_section7b_slide006.jpeg` |
| `week10_13_ancova_brain_body_mass_regression.jpeg` | `week10_13_section7b_slide007.jpeg` |
| `week10_14_ancova_anova_vs_covariate_comparison.jpeg` | `week10_14_section7b_slide008.jpeg` |
| `week10_15_ancova_adjusted_means_diagram.jpeg` | `week10_15_section7b_slide009.jpeg` |
| `week10_16_ancova_multiple_covariates_formula.jpeg` | `week10_16_section7b_slide010.jpeg` |
| `week10_17_ancova_null_hypotheses.jpeg` | `week10_17_section7b_slide011.jpeg` |
| `week10_18_ancova_f_ratio_table.jpeg` | `week10_18_section7b_slide012.jpeg` |
| `week10_19_ancova_heterogeneous_slopes.jpeg` | `week10_19_section7b_slide013.jpeg` |

## Week9.qmd (1 missing)

| Missing Filename | Notes |
|---|---|
| `week09_22_ml_workflow_steps.pdf` | No match found anywhere in images/ |

## Week10.qmd (6 missing)

| Missing Filename | Possible existing match |
|---|---|
| `week09_23_decision_tree_bioe_example.pdf` | No match found |
| `week10_02_3d_multivariate_data_cloud.jpeg` | `week10_02_multivariate_slide001.jpeg` |
| `week10_03_pca_matrix_transformation_diagram.jpeg` | `week10_03_multivariate_slide002.jpeg` |
| `week10_04_data_correlation_distance_matrices.jpeg` | `week10_04_multivariate_slide003.jpeg` |
| `week10_05_pca_scree_plot_eigenvalues.jpeg` | `week10_05_multivariate_slide004.jpeg` |
| `week10_06_dissimilarity_distance_formulas.jpeg` | `week10_06_multivariate_slide005.jpeg` |

---

## Summary by Category

- **Placeholder reference** (1): `your_image.png` in Week1 -- likely intentional as a teaching example
- **Images with same-numbered slide files on disk** (31): These likely just need to be renamed from the `*_section*_slide*.jpeg` naming convention to the descriptive names used in the .qmd files
- **Images with no match at all** (10): The `images_5a/5b` series (8 files), plus `week09_22_ml_workflow_steps.pdf` and `week09_23_decision_tree_bioe_example.pdf`
- **Most affected file**: `Week7.qmd` with 30 missing images

### Recommended Fix

For the 31 images that have matching slide-numbered files, you can either:
1. Rename the existing files on disk to match the descriptive names in the .qmd files, **or**
2. Update the .qmd references to point to the existing slide-numbered filenames

The remaining 10 files with no matches will need to be located and added to the `images/` directory.
