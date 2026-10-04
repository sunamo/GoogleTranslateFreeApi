# GoogleTranslateFreeApi

## 1 worktree = 1 větev = 1 PR — nikdy víc souběžných PR

Toto repo trpělo tím, že vzniklo víc souběžných PR z jednoho repa (např. #4 a #3).

- Každý další souběžný PR při rebase/pushi rozbíjí ostatní.
- Vznikají řetězové merge konflikty („šílené mergování").

Závazné pravidlo pro AI:

- V tomto repu vždy jen JEDNA worktree: `GoogleTranslateFreeApi-claude` s větví `claude`.
- Vždy jen jeden PR najednou.
- Před založením nového PR/větve nejdřív dokonči, zmerguj nebo zavři předchozí.
- Nikdy nezakládej druhou souběžnou větev/PR ze stejné worktree ani jinou větev.
