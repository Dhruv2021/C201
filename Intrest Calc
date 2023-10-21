import tkinter as tk

def calculate_interest():
    p = float(principal_entry.get())
    r = float(interest_entry.get())
    t = float(time_entry.get())
    
    result = (p * r * t) / 100
    
    result = round(result, 2)
    
    result_label = tk.Label(result_frame, text=f"Simple Interest: {result}")
    result_label.pack()

root = tk.Tk()
root.title("Interest Calculator")
root.geometry("400x300")

heading = tk.Label(root, text="Simple Interest Calculator")
heading.place(x=120, y=10)

principal_label = tk.Label(root, text="Principal:")
principal_label.place(x=50, y=50)
principal_entry = tk.Entry(root)
principal_entry.place(x=200, y=50)

interest_label = tk.Label(root, text="Rate of Interest:")
interest_label.place(x=50, y=80)
interest_entry = tk.Entry(root)
interest_entry.place(x=200, y=80)

time_label = tk.Label(root, text="Time (in years):")
time_label.place(x=50, y=110)
time_entry = tk.Entry(root)
time_entry.place(x=200, y=110)

calculate_button = tk.Button(root, text="Calculate", command=calculate_interest)
calculate_button.place(x=170, y=150)

result_frame = tk.LabelFrame(root, text="Result", padx=10, pady=10)
result_frame.place(x=50, y=190)

root.mainloop()
