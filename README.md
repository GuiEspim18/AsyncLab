RM99499 – Guilherme Monteiro Espim RM99279 </br> 
João Paulo Fonseca Zamperlini RM97937 </br>
Pedro Henrique Fernandes Lô de Barros RM97824 </br>
Vinicius Oliveira de Barros </br>
O Program.cs foi alterado para usar operações assíncronas: o download e a leitura do CSV, bem como a escrita de CSV e JSON, passaram a usar async/await. O cálculo de hash PBKDF2 roda em paralelo com Task.Run, aproveitando múltiplos núcleos e reduzindo significativamente o tempo de execução.
