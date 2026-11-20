# SessionSolver prompt development

SessionSolver is an ARIN 121 educational prototype that helps healthy adults create and revise a weekly resistance-training plan using their schedule, available minutes, equipment, training experience, and goal.

## Files

- `system-prompt-initial.md`: initial instructions used in Google AI Studio Playground.
- `system-prompt-cycle-1.md`: complete prompt after clarifying day-count mismatches.
- `system-prompt-cycle-2.md`: complete prompt after making equipment assumptions explicit.
- `system-prompt-cycle-3.md`: complete prompt after adding a checkable session-time budget.
- `system-prompt-cycle-4.md`: complete prompt after specifying revision scope and preservation of constraints.
- `build-prompt.md`: main Build instruction, including the complete Cycle 4 system prompt.

The workbook documents actual tests, short output excerpts, exact changes, and decisions. Some changes clarified behavior that already worked; they are not presented as fixes for invented failures. Later retests reused the active conversation, a limitation of the evidence.

## Limits

This prototype does not provide rehabilitation, prescribe exact weights, assess technique, or guarantee results. Exact programming defaults and the four-week review reminder are application conventions rather than universal ACSM requirements.

## Related project links

The verified application and code-repository links will be recorded in the project workbook when available. Do not treat this local folder as a published GitHub repository.

## Reference

[ACSM resistance-training update, March 17, 2026](https://acsm.org/resistance-training-guidelines-update-2026/)
