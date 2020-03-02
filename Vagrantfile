#!/bin/bash
#Script to update user password

if [$id -u) -eq 1]; then
	read -p "Enter username: " username
	egrep "^$nameuser" /etc/passwd>/dev/null
	if [ $? -eq 0 ]; then
		passwd $username
		echo "Password updated successfully!"
		exit 1
	else
		echo "User does not exist!"
		fi 
