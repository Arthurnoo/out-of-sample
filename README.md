# Out of Sample — notebooks

The code behind every article on [Out of Sample](https://arthurnoo.pythonanywhere.com).

Each notebook reproduces one article from end to end: it downloads its own data,
defines its own functions, and runs top to bottom with no setup from you.

## Run one

| Notebook | Article | Open it |
| --- | --- | --- |
| `buying-the-dip.ipynb` | Does buying the dip work? | [Colab](https://colab.research.google.com/github/Arthurnoo/out-of-sample/blob/main/notebooks/buying-the-dip.ipynb) |
| `risk-neutral-pricing.ipynb` | Why options ignore your forecast | [Colab](https://colab.research.google.com/github/Arthurnoo/out-of-sample/blob/main/notebooks/risk-neutral-pricing.ipynb) |

**In your browser, nothing to install.** Click a Colab link, then Runtime →
Run all.

**In VS Code.** [Clone and open](vscode://vscode.git/clone?url=https://github.com/Arthurnoo/out-of-sample),
or by hand:

```bash
git clone https://github.com/Arthurnoo/out-of-sample
cd out-of-sample
pip install -r requirements.txt
```

Then open any notebook, pick a Python interpreter in the top right, and Run All.
The first cell installs anything still missing, so this works either way.

## How they are built

Every notebook has a **Section 0** holding every parameter worth changing, with
a table explaining what each one does and what to try. Everything after it
follows from those values. Change one, run again, and see what moves.

The last section of each notebook suggests four changes that would genuinely
test the result rather than confirm it.

## Found a mistake?

Each article has a form at the bottom. A wrong number corrected in public is
worth more than a right one nobody checked.
