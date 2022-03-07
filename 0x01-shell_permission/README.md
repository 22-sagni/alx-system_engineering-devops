WHAT THE FILES EXECUTE
1. 0-iam_betty :- switches the current user to the user betty
2. 1-who_am_i :- prints the effective username of the current user
3. 2-groups :- prints all the groups the current user is part of 
4. 3-new_owner :- changes the owner of the file hello to the user betty
5. 4-empty :- creates an empty file called hello
6. 5-execute :- adds execute permission to the owner of the file hello
7. 6-multiple_permission :- adds execute permission to the owner and the group owner, and read permission to other users
8. 7-everybody :- adds execution permission to the owneer, the group owner and the other users, to the file hello
9. 8-James_Bond :- sets the permission to the file hello to; owner and group no permission at all, other users have all 	the permission
10. 9-John_Doe :- sets the mode of the file hello to 753 (chmod 753 hello)
11. 10-mirror_permission :- duplicates the mode of the file olleh to that of hello
12. 11-directories_permission :- adds execute permission to all subdirectories of the current directory for the owner,
	the group owner and all other users while regular files are kept intact
13. 12-directory_permission :- creats a directory with permission 751 in the working directory
14. 13-change_group :- changes the group owner to school for the file hello
15. 100-change_owner_and_group :- changes the owner to vincent and the group owner to staff for all files and           	 directories in the working directory
16. 101-symbolic_link_permission :- changes the owner and group owner of _hello to vincent and staff respectively
17. 102-if_only :- changes the owner of the file hello to betty only it is owned by the user guillaume
18. 103-star_wars :- plays the wars IV episode in the terminla
