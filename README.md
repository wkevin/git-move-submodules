git-move-submodules
===================

## Target
Move all submodules in "Folder" from its parent dir "foo" to another dir "bar".

## Require
When I collect many submodules ,it is necessary to move them from one folder to another folder for ordering them. Genearaly we put submodules in a independent folder,such as vender whitch parent folder such as foo. So, I want to move all submodules in this vender folder from "foo" to another path (such as "bar" folder) with same direction tree struction inside the vender.

## Usage

    usage: ./git-move-submodules [-v] [-t] foo/Folder bar/
    Folder's all submodules will move from foo to bar
    [-v] verbose
    [-t] test: only show whitch submodule will move without real move
	Attention:
	1.git-move-submodules file must in same dir with .gitmodules
	2.bar must exist 
    3.foo can be NONE
  

## Reference
http://github.com/wkevin/iOS.faculty


