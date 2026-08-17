THE GHOSTS OF SPARTA — versão com Firebase

O index.html foi preparado para sincronizar estes dados pelo Firestore:
- gow_members
- gow_scores
- gow_champions_ligas
- gow_battle_groups
- gow_battle_managers

Importante:
1. No Firebase Console, Authentication > Método de login: Google deve continuar ATIVADO.
2. No Firestore, publique o arquivo firestore.rules.
3. O site permite leitura pública dos dados e exige login Google para gravar alterações.
4. No site, use "Entrar para sincronizar" antes de cadastrar/editar dados.
5. A cópia original não foi alterada; esta pasta é a versão preparada.

Observação: o Firebase Web SDK usa módulos CDN, portanto o site deve ser aberto/servido por HTTPS ou por um servidor local, e não depender de abrir o arquivo diretamente com file://.
