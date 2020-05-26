# template-collection

A template repo for creating new collections. 

*Don't fork this repo*. Instead, use the green "Use this Template" button in Github. 


Collections are composed of this top level directory and source packages that
are included a git submodules. So, to add a few packages:

  
    git submodule add https://github.com/metatab-packages/sandiegocounty.gov-covid19.git
    git submodule add https://github.com/metatab-packages/census.gov-boundaries-2018.git
    
Then, when checking out the collection, be sure to update all of the submodules too: 

    git clone --recurse-submodules <collection_url>
    
    