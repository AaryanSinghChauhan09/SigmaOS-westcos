# SigmaOS-westcos

SigmaOS integration component for **WestCOS driver**.

## Commands

```bash
sigmaos-westcos install   # install package + deploy defaults
sigmaos-westcos deploy    # copy config templates to $HOME
sigmaos-westcos status    # binary/package/config report
sigmaos-westcos reset     # remove deployed config
sigmaos-westcos open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
