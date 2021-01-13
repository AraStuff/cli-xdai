# aragonCLI for xDAI
after cloning and installing this repo, you will be able to run aragonCLI commands on xDAI

1. clone and install this repo `git clone https://github.com/AraStuff/cli-xdai.git && cd cli-xdai && yarn`

2. ensure you have the aragonCLI installed and set up on you local machine. you can find a guide [here](https://forum.aragon.org/t/aragon-cli-setup-guide/1934)

3. create a xdai key `~/.aragon/xdai_key.json`
```
{
  "rpc": "https://rpc.xdaichain.com",
  "keys": ["put-your-priv-key-here"]
}
```

## running commands
you can now run aragonCLI commnds against the xDAI network from in your terminal from within this folder by adding `--env xdai` to your command
