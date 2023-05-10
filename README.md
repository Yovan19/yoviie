# yoviie


from software_engineer import ( SoftwareDeveloper, ProgrammingSkills )
import os


class Designation(SoftwareDeveloper):

  def __init__(self):
    self.employee_name     =    'Yovan Patel'
    self.employee_title    =    'Software Engineer'
    self.company_name      =    'Einzigartige'
    self.location          =    'Vesu Surat'  



class MySkills(ProgrammingSkills):

  def  __init__(self):
    self.programing_language      =    ( 'PHP', 'Python', 'JavaScript' )
    self.databases                =    [ 'MySQL', 'MongoDB', 'SQLite', 'PostgreSQL' ]
    self.backend_frameworks       =    { 'Laravel', 'NodeJS', 'WordPress', 'Django' }
    self.frontend_frameworks      =    [ ( 'NextJS' ) , ( 'VueJS' ), ( 'ReactJS' ), ( 'AngularJS' )  ]  
    self.tech_stack               =    [ { stack: 'LAMP Stack' } , { stack : "WAMP Stack" }, { stack : "XAMPP Stack" } ]
    self.learning_and_focusing_on =    ( 'ReactJS with NextJS', 'FAST API', 'Django', 'AWS Services', 'CI & CD Development' )



def know_more_about_me(designation: Designation, my_skills: MySkills):
  """
  Want to visit my portfolio site?
  """
  
  from computer import GoogleChrome
  
  # My Portfolio is Under Construction Mode.   😉 
  visit_my_portfolio_website = "http://einzigartige.in/"
  GoogleChrome.search_in_new_tab(visit_my_portfolio_website)
 
  
def know_me():
  designation =  Designation()
  my_skills    =  MySkills()
  know_more_about_me(designation, my_skills)
  

if __name__ == "__main__":
    know_me()
    os.system("exit()")
    

"""
Did you found any BUGs on this code. 🤔
"""
