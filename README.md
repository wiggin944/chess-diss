# Behavioural Economics Dissertation: Risk Preference in Chess

Research summary for my BSc Economics dissertation, which received **77% (First-class)**.

## Research question

The project investigated whether framing effects persist in a more complex strategic environment than the simple laboratory choices commonly used in behavioural economics. Chess provided a useful middle ground: decisions are structured and measurable, but still require forward-looking judgement under uncertainty.

## Approach

The dissertation combined:

- an encrypted SQL database connected to Python data-collection scripts
- experimental framing treatments
- OLS regression with interaction terms
- a recursive algorithm for simulating future chess positions
- a risk measure based on the variance of centipawn evaluations across predicted future states

Rather than defining risk as a simple best-to-worst range, the recursive procedure represented risk as the dispersion of plausible future outcomes.

## Results

The final regression specification achieved **R² = 0.221**. The analysis found that:

- negative framing was associated with greater risk-seeking among higher-skilled players
- positive framing was associated with overconfidence-driven risk-seeking
- both framing effects were moderated by player skill

## Why it matters

The project combined behavioural economics, econometrics, database design and algorithmic modelling in a single empirical study. It was an early example of the type of work I now focus on in data science: turning a behavioural question into a measurable data-generating process, engineering a usable dataset, and testing the resulting hypothesis statistically.

## Repository note

This is a lightweight public research summary. The full participant data, encrypted database and complete experimental/analysis pipeline are not published here.

## Author

William Higgin
