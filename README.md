A API do Yahoo, foi descontinuada. Para simplificar, fizemos um mock das infos necessárias e hospedamos no functions. Substituir:

    var url = 'https://query.yahooapis.com/v1/public/yql?format=json&q=' + statement;
 

para:


    const url = 'https://us-central1-gdg-mogiguacu-229701.cloudfunctions.net/gdg-guacu-pwa?city=' + key;


é isso aí, :D
