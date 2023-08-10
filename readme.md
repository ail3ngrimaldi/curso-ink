# Curso ink!

En este repositorio iré subiendo mi progreso en el curso de ink! dictado por Polkadot.

# Clase 1 

En la primera clase debíamos configurar nuestro entorno de desarrollo y ejecutar nuestro primer contrato. A continuación se detallan los pasos a seguir, utilizando como OS Linux Mint 21.1 Cinnamon.

En mi caso Rust ya estaba instalado en mi ordenador, por lo que dejo acá <a href="https://github.com/Juminstock/ink_toolkit">una referencia</a> en caso de que quieras realizar el proceso desde cero.

Por mi parte seguí los pasos preventivamente para no tener errores posteriores, y al estar todo instalado simplemente ejecuté

<div align="center">
    <code>cargo install cargo-contract --force --locked</code>
</div>

Tras lo cual al no obtener errores, cree mi primer contrato con

<div align="center">
    <code>cargo contract new flipper</code>
</div>

Por último ejecuté el siguiente comando, ya que el compilador señalaba tres errores que se solucionaron inmediatamente.

<div align="center">
    <code>rustup default stable</code>
</div>
