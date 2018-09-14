# Ruby Project 1
  -----
  This is an assignment which is making us familiar with ruby and the its syntax.
  This file consists of 7 parts:
  
  - Short Questions
  - Problem
  - Documentation
  - Thinking Assignment
  - API intro
  - License
  - Author
   ---

# Getting Started
   ** Install the Ubuntu Bash to run the program
       Clone/Download the solutions and then run the main.rb

    # Download all files from canvas as they are Ubuntu scripted.
    # For Ubuntu
    $ ruby main.rb
    
---
# Parts
 - Short Questions
 - Problem
 - Documentation
 - Thinking assignment

# Short Questions
  There are 8 short questions given in this part.
  All the questions in this part were based on syntax and methods, just to prepare us for the problem that had to be sloved using them.
  It started from printing "HELLO WORLD", moving to data structures and breif concepts of object oriented programming.
  
# Problem
  
  This is an interesting question which asks to update the search list everytime. Let me be very precise, if we search a movie name and then do another search, the latest search should be placed in front of the old search and has to be saved and printed.
  
  Usually we need to create an array which is updated, saved, and which prints the latest updated list.
  
# Documentation
  
  The third part is the documentation for this assignment. It is nothing but creating README file by entering the all the content that we are doing in this assignment. Basically this is report for the assignment.
  
# Thinking Assignmnet
  
  The final part is the thinking assignmnet. We were asked to find the logic to find the number where sudden fluctuation of value takes palce.

---  
# API Intro
  
  class SearchController

	attr_accessor :searchSuggestionList

	def initialize(search_list = [])
		#<TODO: write your code here>
		@searchSuggestionList = []
		search_list.each do |item|
			@searchSuggestionList << item 
		end
    end
  Some API's are written by author like updateList depending upon the problems demand.  
  
    def updateList(movie_name)
		#<TODO: write your code here>
		@searchSuggestionList.insert(0,movie_name)
	end
	
---
# Implementation of Search Controller
  In the lower end, the class uses Queue to update the search list.

---
# Program complexity
  The program runs with a time complexity of O(n).

---
# Results
  Gives the updated list after doing multiple searches.
 
---
# License
  Auburn University

---  
# Author
  Karthik Karra
  
  





