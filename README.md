Here are the available commands and their functions:

*   `/start`: Initializes the QA task. I will ask for all required context variables (`TASK_TITLE`, `TARGET_AUDIENCE`, etc.).
*   `/run html`: Formats the raw PT Request document into a clean, readable HTML view.
*   `/run progression_map`: Combines the question order and ID mapping into a single table and initializes the Master Feedback Log.
*   `/run alignment`: Checks if the built PTs align with the original PT Request document.
*   `/run comprehensive`: Performs a holistic review of all PTs against the full PT Creator Handbook.
*   `/run skill_check`: Checks if each PT measures one of the skills from the provided list.
*   `/run check [check_name]`: Runs a specific, targeted QA check on the PTs. Replace `[check_name]` with one of the following:
    *   `Hint_Structure`: Reviews hint quality, structure, and placement.
    *   `Forbidden_Words`: Checks for forbidden/discouraged words like 'you', 'need', 'must'.
    *   `Randomization_Logic`: Verifies specific `<mathyon-r>` setups for equation SPTs.
    *   `Language_Tone`: Reviews the overall language and tone.
    *   `Localization`: Checks for correct regional terminology (AU/US).
    *   `Grade_Level`: Assesses if the content is appropriate for the target grade.
    *   `Math_Accuracy`: Reviews for mathematical correctness and formatting.
    *   `Solution_Paths`: Checks the granularity and logic of solution steps.
    *   `Realistic_Randomization`: Assesses if randomization produces believable scenarios.
*   `/add_my_feedback [PT_ID]`: Allows you to add your own manual feedback for a specific PT.
*   `/add_general_feedback`: Allows you to add high-level feedback that applies to the entire PT set.
*   `/show_feedback_table`: Displays the current state of the Master Feedback Log as a TSV table.
*   `/generate_report`: Generates the final, synthesized feedback report formatted for ClickUp.
*   `/help`: Displays this list of commands.
