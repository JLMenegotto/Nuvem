# Nuvem
Aplicação de Revit para trabalhar com nuvem de pontos.

#### Instalação para executar em Revit como API 
 
#### Arquivo Addin para Revit
Incorporar o conteúdo do arquivo **Nuve2025.addin** na lista de aplicações do seu sistema. A pasta que contém do arquivo de addins é **C:\ProgramData\Autodesk\Revit\Addins\2025**. Caso decida instalar a API numa outra pasta da sua preferência, deverá alterar o caminho presente no conteúdo do arquivo ONTO2025.addin  

<AddIn Type="Command">
	 <Assembly>C:\Pasta_de_instalação\Nuve_2025.dll</Assembly>
	 <AddInId>106715fe-8dff-4d23-9080-a82a34c92fe8</AddInId>
	 <FullClassName>NUVEM.Nuvem</FullClassName>
	 <Text>Nuvem_2025</Text>
  	 <VisibilityMode>AlwaysVisible</VisibilityMode>
	 <VendorId>JLM</VendorId>
	 <VendorDescription>JLM_UFRJ</VendorDescription>
</AddIn>

#### Interface:

![Interface_01](https://github.com/user-attachments/assets/6ce06474-c195-42ec-8615-f94a70ed3c1e)

O botão carrega é o primeiro processo a ser executado. A aplicação vai ler o arquivo Nuvem.txt e insere o arquivo rcs com os valores de deslocamento XYZ e rotação.
A análise dos pontos com finalidade de modelagem ou visualização podem ser feitos a partir dos andares ou dos eixos estruturais definidos no modelo Revit. 
Os botões Corte-H e Corte-V utilizam o andar ou o Eixo selecionado nos campos. Os valores numéricos aumentam ou deslocam as faixa de pontos selecionados.
O botão Isola é utilizado para mostrar apenas os pontos selecionados no corte.

#### Exemplos de cortes de análise da nuvem:

###### Corte horizontal sobre o Andar 3
![Horizontal_01](https://github.com/user-attachments/assets/2c9e6e24-e248-4cc4-8381-c97d057b695d)

###### Corte horizontal sobre o Andar 3 isolado
![Horizontal_02](https://github.com/user-attachments/assets/606a3694-0dd9-4824-a9e6-50bcf62f8013)

###### Corte vertical sobre o eixo 6
![Vertical_01](https://github.com/user-attachments/assets/741afd09-9b33-4cc1-a610-5b9ad1ef80a8)

###### Corte vertical sobre o eixo 6 isolado
![Vertical_02](https://github.com/user-attachments/assets/966e9895-bd03-4d3d-a2ea-7f1f80e29eed)

###### Corte vertical sobre o eixo 6 isolado
![Vertical_03](https://github.com/user-attachments/assets/c6d80f0f-a7bf-422b-b309-61b1d8ccdb88)




