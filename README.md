Features
✔ Convert between common length units (meters, feet, inches, yards, etc.)
✔ Basic arithmetic operations (add, subtract, multiply lengths)
✔ Clean, intuitive API with zero dependencies
✔ Type hints for better IDE support

Quick Example
python
from py_length import Length  

# Convert 5 meters to feet  
length = Length(5, "m")  
print(length.to_feet())  # Output: 16.4042  

# Add two different units  
total = Length(2, "m") + Length(3, "ft")  
print(total.to_inches())  # Output: 118.11023622  
Installation
bash
pip install py-length  
Why py-length?
✅ Beginner-friendly – No complex dependencies.

✅ Extensible – Add custom units easily.

✅ Practical – Useful for engineering, physics, and everyday conversions.

Contributions welcome! 🚀
