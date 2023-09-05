# Original Repository: https://github.com/projectdiscovery/pd-actions

#### Edit File in `.github/workflows/*` and change In

```
      - name: 👨🏻‍💻 Commit results to Github
        run: |
          git config --local user.email "YOUR_EMAIL_GITHUB"
          git config --global user.name "USERNAME"
          git commit -m "PD-Actions report" -a --allow-empty
```

#### Input Target Single domain `input/domains.txt`
#### Note: Remove `actions/caches` after scanning to avoid errors.
