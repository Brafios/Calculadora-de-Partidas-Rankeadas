
function numberVictories()
{
	let cont = 0
	let numberVictories = 0
	for (cont = 0; cont < 90; cont++)
    {
        numberVictories++
    }
    return numberVictories
}

function numberDefeats()
{
	let cont = 0
	let numberDefeats = 0
	for (cont = 0; cont < 10; cont++)
    {
        numberDefeats++
    }
    return numberDefeats
}
   
function balance()
{
	let balance = numberVictories() - numberDefeats()
	if (balance <= 10)
	{
		nivel = "ferro"
	}

	else if (balance <= 20)
	{
		nivel = "bronze"
	}

	else if (balance <= 50)
	{
		nivel = "prata"
	}

	else if (balance <= 80)
	{
		nivel = "ouro"
	}

	else if (balance <= 90)
	{
		nivel = "diamante"
	}

	else if (balance <= 100)
	{
		nivel = "lendário"
	}

	else 
	{
		nivel = "imortal"
	}
    
    console.log("O Héroi tem saldo de vitórias de: " + balance + " está no nivel: " + nivel)
    
}

balance()
