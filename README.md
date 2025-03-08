import json
import os
class Person:
    def _init_(self, name, age, email):
        self.name = name
        self.age = age
        self.email = email
    
    def _str_(self):
        return f"Name: {self.name}, Age: {self.age}, Email: {self.email}"
    
    def display_info(self):
        return f"Person: {self.name}, {self.age} years old, {self.email}"

class Student(Person):
    def _init_(self, name, age, email, student_id, grades):
        super()._init_(name, age, email)
        self.student_id = student_id
        self.grades = grades
    
    def display_info(self)
        return f"Student: {self.name}, ID: {self.student_id}

class Teacher(Person):
    def _init_(self, name, age, email, teacher_id, subject):
        super()._init_(name, age, email)
        self.teacher_id = teacher_id
        self.subject = subject
class Course:
    def _init_(self, course_name, teacher, students):
        self.course_name = course_name
        self.teacher = teacher
        self.students = students 
  
