# Bancodigital
package com.company;

public class Main {

    public static void main(String[] args) {
	Conta cc = new ContaCorrente();
    Conta poupança = new ContaPoupanca();

    cc.depositar(100);
    cc.transferir(200, poupança);

        cc.imprimirExtrato();
        poupança.imprimirExtrato();
    }
}
