def conversor(grados_cent):
    Fahrenheit = (9 / 5) * grados_cent + 32  # transformado centigrados a faren
    Kelvin = 273.15 + grados_cent             # transformación de grados centígrados a kelvin

    return Fahrenheit, Kelvin

centigrados = int(input("Ingrese grados centígrados: "))

result_far, result_kelvin = conversor(centigrados)

print(centigrados, " grados centígrados es igual a ", result_far, " grados Fahrenheit")
print(centigrados, " grados centígrados es igual a ", result_kelvin, " grados Kelvin")
