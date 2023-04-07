# search
code base search using grep and find
examples: `basename $0` 'isLoaded' '*.[php]'                    # fixed string search -w
          `basename $0` '(account_entity|isLoaded)' '*.[php]'   # regular expression search -E
          `basename $0` '-F' 'isLoaded(' '*.[php]'              # force fixed string search
          `basename $0` '-L -F' 'isLoaded(' '*.[php]'           # search for files not having the search criteria"
