# configure git diff to understand notebooks
```
echo "*.ipynb diff=ipynb" >> .gitattributes 
git config diff.ipynb.textconv nbflatten.py
```

via @thead
https://gist.github.com/takluyver/bc8f3275c7d34abb68bf
