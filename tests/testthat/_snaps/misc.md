# check_new_data works

    Code
      bake(log_obj, examples[, 2:4, drop = FALSE])
    Condition
      Error in `step_log()`:
      ! The following required column is missing from `new_data` in step 'log_IhS7o': V1.

---

    Code
      bake(log_obj, examples[, 3:4, drop = FALSE])
    Condition
      Error in `step_log()`:
      ! The following required columns are missing from `new_data` in step 'log_IhS7o': V1 and V2.

---

    Code
      bake(log_obj, examples[, 4, drop = FALSE])
    Condition
      Error in `step_log()`:
      ! The following required columns are missing from `new_data` in step 'log_IhS7o': V1, V2, and V3.

