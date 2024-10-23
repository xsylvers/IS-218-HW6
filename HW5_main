from commands.add_command import AddCommand #type: ignore
from commands.subtract_command import SubtractCommand # type: ignore
from commands.multiply_command import MultiplyCommand # type: ignore
from commands.divide_command import DivideCommand #type: ignore
from calculator import Calculator  # Assuming the REPL logic and plugin loader are in calculator.py

if __name__ == "__main__":
    calc = Calculator()
    calc.register_command('add', AddCommand())
    calc.register_command('subtract', SubtractCommand())
    calc.register_command('multiply', MultiplyCommand())
    calc.register_command('divide', DivideCommand())
    
    calc.load_plugins()  # This line of code loads up any additional plugins dynamically
    calc.repl()          # This line of cards starts up the REPL
