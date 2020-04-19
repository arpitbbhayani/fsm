FSM using Python Coroutines

 - Divisibility by 3
 - SQL Parser
 - Regular Expression `ab*c`

# Setup
## Install GraphViz

```
brew install graphviz
```

## Install requirements

```
pip -r requirements.txt
pip install --install-option="--include-path=/usr/local/include/" --install-option="--library-path=/usr/local/lib/" pygraphviz
```

## Exporting images from DOT

```
dot -Tpng -Gsize=9,15\! -Gdpi=200 -oregex-1.png regex-1.dot
dot -Tpng -Gsize=9,15\! -Gdpi=200 -odiv3.png div3.dot
dot -Tpng -Gsize=9,15\! -Gdpi=200 -osql.png sql.dot
dot -Tpng -Gsize=9,15\! -Gdpi=200 -otraffic-signal.png traffic-signal.dot
```
