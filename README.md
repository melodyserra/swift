# Swift

## Let's start by talking about what iOS is:
- "an operating system used for mobile devices manufactured by Apple Inc."

## What is Xcode?
- Xcode: complete piece of software that allows you to design, code, and submit an app. 
- Let's take a look at Xcode and how it works. Let's also work with the **storyboard**. 

## Swift
- New language announced in June 2014. 
- Playgrounds allow you to run code immediately and see the results. 
- Let's go over what you will see at the beginning of your code base and what it means:

	- `import UIkit` imports a range of functions and methods that allow you to interact with the user interface.
	- This will be followed by this:

	```
	class ViewController: UIViewController {
	    override func viewDidLoad() {
	        super.viewDidLoad()
	        // Do any additional setup after loading the view, typically from a nib.
	    }
	    override func didReceiveMemoryWarning() {
	        super.didReceiveMemoryWarning()
	        // Dispose of any resources that can be recreated.
	    }
	}
	```

- `println("Hello World!")` allows you to print simple code in your log(the console). Why would we want to do this?  

- `var` creates a variable, when you want to set it equal to a value you place it in quotes. 
- `variable` = bucket or store for a particular value.
- Swift is very sensitive to types of variables. 
- To update a variable:
	
	```
	var str = "Hello"
	str = "Goodbye" 
	```
- To specify that a variable is a **string**(a collection of characters):
	
	`var name:String = "Mel"`
	
- **Integers** are whole numbers (example: used if you are counting the number of users in your database).
	
	```
	var int = 4
	4 * int
	```
	- To specify that a variable is an integer:
	
	 `var a:Int = 5`
	
- **Double** specifies that the number is a decimal:
	
	 `var c:Double = 3 / 2`
	
- Can't combine integers and doubles, need to convert integer in to a double: `c*Double(int)`
	
- **Three core variables: strings, integers, doubles.**

	`var longSentence = str + name`
	
- **Array** is a collection of variables (example: you want to store all of the user's posts, can then loop through them and search for a particular one).

	`var arr = [1, 2, 3]`
	
	- If you wanted to access the 3rd variable:
	
		`arr[2]`
	
	- To add an item to an array:
	
		`arr.append(4)`
	
- An array is ordered, a **dictionary** is not.

	`var dict = ["name": "Mel", "age": 28, "gender": "female"]`
	
	`println(dict["name"])`
	
-----------------------------------Practice Time----------------------------------------	

- Prompt: Create a program in Swift where you ask a user to enter the age of their dog or cat. Assume they will round to the nearest whole year. The program will then take the age entered, say 2, and multiply it by 7. This will give you the age entered in cat or dog years. 
	
	
	
	
	