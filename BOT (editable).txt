import random
listapersone=['Il bomber', 'Zeman', 'Spalletti', 'Vucinic', 'De Rossi','er monezza','Ilary', 'Cassano', 'Del Piero', 'Mattarella', 'Murigho', 'Immobile', 'Berlusca', 'er tifoso daa lazio', 'er tifoso daa Roma', 'er tifoso daa Magica', 'Cortese, un immigrato']
listafrasi=['hai cacato?','daje roma', 'quando torni?', 'Oerd diventa italiano', 'e sti cazz do li piazzi', 'cacapalina', 'il nuoto è lo sport più completo', ' si stava meglio quando si stava peggio', "i guai so de chi non ce l'ha"]
listafrasitotti=['forza roma','porco dio', 'porca madonna', 'lazio merda']
listaluoghi=['nello Spogliatoio', ' al Bar','ostia','a ostia lido','a pottane','allo stadio', 'a fanculo', 'a Latina', 'ar cleb daa lazio','ar cleb daa magica']
listapersoneplurali=[]

x=random.randint(0,len(listapersone)-1)
y=random.randint(0,len(listafrasi)-1)
z=random.randint(0,len(listafrasitotti)-1)
h=random.randint(0,len(listaluoghi)-1)

print('Totti va',listaluoghi[h],'incontra',listapersone[x],
      'che glie dice:"A FRANCIEE,',listafrasi[y],'"', 'e totti glie dice:"',
      listafrasitotti[z],'"')