from pyscript import document, display

# COMPUTATION TO FIND THE AVERAGE OF TWO NUMBERS FROM 1 TO 100
def avg_system(e):

    # FLOAT VARIABLES FOR GRADE CALCULATION, DEFAULT IS 0
    num1 = float(document.getElementById("num1").value or 0)
    num2 = float(document.getElementById("num2").value or 0)

    # COMPUTES THE AVERAGE OF TWO NUMBERS
    average = (num1 + num2)/2
    document.getElementById("average").innerText = f"⭐ Your average is {average}"

    # TO SHOW INPUT IF NULL OR NOT
    if not (1 <= num1 <= 100 and 1 <= num2 <= 100):
        document.getElementById("average").innerText = "⚠️ Uh oh! You have an invalid average!"
        document.getElementById("result").innerText = "‼️ Are you sure you input a number from 1 to 100?"
        return

    # PASS/FAIL DETERMINER
    if average >= 75:
        document.getElementById("result").innerText = "✔️ Congratulations! You passed!"
    else:
        document.getElementById("result").innerText = "❌ Sorry.... You failed."
