### Hi there 👋

My name is Anastasis Tsolakos:




#!/usr/bin/python
# -*- coding: utf-8 -*-

class Me:
  """A class to represent a person."""
    
  def __init__(self):
    self.name = "Anastasios Tsolakos Agkistriotis"
    self.nickname = "Anastasis"
    self.role = "Student"
    self.employer = "Athens University of Economics & Business"
    self.bsc_studies = ("Computer Science", "Dept. of Informatics", "Athens University Of Economics & Business")
    self.language_spoken = ["el_GR", "en_US"]
    self.country = "Greece"
    self.city = "Athens"
        

  def say_hi(self):
    print("Thanks for stopping by, hope you find some of my work interesting! Sincerely, ", self.nickname, ".", sep = "")


anastasis = Me()
anastasis.say_hi()
