# Mythril-repo
idk just testing<br>
command: ``myth analyze <file> -o json --max-depth 50`` -> myth-json.py automatiza o transferimento da analise pro json



<ul>
<h3>CryptoKitties</h3>    
    <li><i><b> /contracts/GameVarAndFee.sol: </b></i> Erro com a versao do authority/Owned.sol, todos os contratos usam solidity 0.5.5 e o Owned usa 0.5.0. Alterando a versao dele nao muda o resultado.</li>
    <li><i><b> /contracts/CronJob.sol: </b></i>Mesmo erro de versao do authority/Owned.sol</li>
    <li><i><b> /contracts/DSNote.sol: </b></i> Nenhum erro foi detectado. Checar DSNote_analyzed.json no repositorio. </li>
    <li><i><b> /contracts/authority/Owned.sol </b></i> Falha identificada - Exception State: an assertion violation was triggered. Checar Owned_analyzed.json no repositorio.</li>
    <li><i><b> /contracts/ </b></i> </li> 
</ul>
