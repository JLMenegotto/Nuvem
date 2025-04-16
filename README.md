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

![Corte_01](https://github.com/user-attachments/assets/5efe97c8-c359-4208-a2ef-56275f3012ba)

![Corte_02](https://github.com/user-attachments/assets/6ba112f7-1851-46d2-8070-74ff386eeb2a)

![Corte_03](https://github.com/user-attachments/assets/7f114a80-9369-4e9d-b643-d88266f8c26c)

![Corte_04](https://github.com/user-attachments/assets/bcc21723-5d9e-472a-888f-b146f0a1649f)

![Corte_05](https://github.com/user-attachments/assets/810a067e-748b-4d90-9e87-01467aeec966)
