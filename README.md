const nome = "Mario";
const xp = 7500;

const niveis = [
    { minimo: 0, maximo: 1000, nome: "Ferro" },
    { minimo: 1001, maximo: 2000, nome: "Bronze" },
    { minimo: 2001, maximo: 5000, nome: "Prata" },
    { minimo: 5001, maximo: 7000, nome: "Ouro" },
    { minimo: 7001, maximo: 8000, nome: "Platina" },
    { minimo: 8001, maximo: 9000, nome: "Ascendente" },
    { minimo: 9001, maximo: 10000, nome: "Imortal" },
    { minimo: 10001, maximo: Infinity, nome: "Radiante" }
];

let i = 0;
let nivel = "XP inválido";

while (i < niveis.length) {
    if (xp >= niveis[i].minimo && xp <= niveis[i].maximo) {
        nivel = niveis[i].nome;
        break;
    }

    i++;
}

console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
```


## Mario

Experiência: 7.500 XP

O Herói de nome Mario está no nível de Platina 🚀


  
