# Remove  duplicated files on OS X and Linux

Quick Tutorial how to find and delete duplicated files on a UNIX based system.  
I wasted quite some time to find this nice tool, so hopefully i can help save your time. 

The right tool to do the job is [fdupes](https://github.com/adrianlopezroche/fdupes).

### OS X Installation:  
`brew update && brew install fdupes`   

### Linux (apt based)  
`apt-get update && apt-get install fdupes`

### Usage
`fdupes -r -d -N  /folder/with/duplicated/files/`   **attention: deletes directly!**  

> -r recursive  
> -d delete  
> -N don't ask, just delete  

[![frapsoft on twitter](https://static.frapsoft.com/markdown/github/twitter.png)](https://twitter.com/frapsoft)

## License

Copyright (c) 2016 Maik Ellerbrock  
MIT: <https://opensource.org/licenses/mit-license.php>