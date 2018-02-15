## Change Log

2.14.2018  
- This is a fork of block chain tools, original credits goes to **Alex Gorale**
- This version is ported from Python2 into Python3
- Planned feature: add ability to parse multiple block files at onetime

## Block Chain Tools

Block chain parser implementation written in python. Contains examples for Bitcoin and Litecoin.

- blocktools.py - tools for reading binary data from block files
- block.py - classes for Blocks, Transactions
- parser.py - Genesis block demo
- sight.py - block parser
- 5megBlock.dat - first 5 megs from blk00000.dat
- blk65.dat - first 5 megs from blk00065.dat

## Usage

```bash
python sight.py 1M.dat
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Credits

Alex Gorale

## License

BSD 3
