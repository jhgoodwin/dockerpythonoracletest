This is an example python docker container with several scientific and math libraries added.

The point of this particular example is to accept an oracle connection string, then print the version property after connecting.  This value is found on the connection object as .version
To run this command, use something like this:
```
docker run --rm -e "ORACLE_CON_STR=YourUserNameHere/YourPasswordHere@IpAddressOrHostnameOfOracleServerHere/OracleInstanceNameHere" jhgoodwin/pythontest
```

