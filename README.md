```py
class AboutMe:
	@staticmethod
	def contact() -> tuple:
	    facebook  = "Utsav Adhikari"
	    instagram = "Utsav Adhikari"
              linkedin = "raju-xz"
	    email   = "utsavadhikari452@gmail.com"
	    
	    return facebook,instagram,email
	
	@staticmethod
	def about() -> tuple:
		langs         = ['Nepalese', 'English', 'Hindi']
		nationality = ['Nepali']
		age           = 22
		
		return langs, nationalitiy, age
	
	@staticmethod
	def specs() -> tuple:
		langs = {
			'expert':   ['Java',"C#"],
			'intermediate': ['python', 'js'],
			'learning': ['Django', 'Vue', 'Flask', 'AI/ML','Android']
		}
		specialities  = ['fullstack']
		environnement = ['vscode','Android Studio','Visual Studio']
		
		return langs, specialities, environnement
                    
if __name__ == "__main__":
          AboutMe.contact()
          Aboutme.about()
          Aboutme.specs()
          
 ```
          
