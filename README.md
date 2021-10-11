# gitpa



git rm --cached file3.txt
	-removes file from staging area and moves it 	back to the untracked files
	-does not remove from outr working directory
	-can only be done when no commit has been 	done

git ls-files -s
	-check the satging area
---------------------------------------------------------

git checkout

	-jump to certain version of project
	
-------------------------------------------------------
git cat-file -p 4digitsofcommitid

	-details like tree parent author and commitor
	
git cat-file -t 4digitsoftreeid
	--details of the tree like blob
	-after deleting all files if do this tree will be empty as there is no blob
