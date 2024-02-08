# Dio - Microsoft Azure AI Fundamentals - Reconhecimento Facial e transformação de imagens em Dados no Azure ML

O Azure oferece uma gama de serviços de imagem com IA que podem ser facilmente integrados em seus aplicativos e projetos. Aqui está um guia detalhado sobre como usar os serviços "Detectar faces em uma imagem", "Extrair texto de imagens" e "Adicionar legendas a imagens", incluindo insights e possibilidades para cada serviço.

1. Detectar Faces em uma Imagem:
- Processo:
    - a. Upload da imagem: Comece carregando a imagem desejada para o serviço Visão de IA do Azure. Você pode usar o portal do Azure, SDKs ou APIs RESTful.
    - b. Detecção de faces: O serviço usa algoritmos de aprendizado de máquina para detectar rostos na imagem. Ele fornece informações como a localização de cada rosto, probabilidade de ser um rosto, pontos de referência faciais e detalhes como idade, gênero, emoção e óculos.
    - c. Acesso aos resultados: Os resultados da detecção de faces podem ser acessados em formato JSON ou XML. Você pode usar esses dados para diversos fins, como autenticação biométrica, análise de sentimento, marcação de fotos e muito mais.
- Insights e Possibilidades: Este serviço é uma ótima ferramenta para aprender sobre aprendizado de máquina e visão computacional. Você pode usar a API para criar seus próprios projetos de detecção de faces, como um sistema de reconhecimento facial para sua casa ou um aplicativo de análise de sentimento.

*Detect faces in an image*
![harcanjo](./prints/Screenshot%202024-02-08%20154413.png)
![Joker](./prints/Screenshot%202024-02-08%20154159.png)
![store-camera-1](./prints/Screenshot%202024-02-08%20160743.png)

2. Extrair Texto de Imagens:
- Processo:
    - a. Upload da imagem: Carregue a imagem com texto para o serviço OCR (Reconhecimento Óptico de Caracteres) do Azure.
    - b. Reconhecimento de texto: O serviço usa OCR para extrair o texto da imagem. Ele suporta diversos idiomas e formatos de texto, como documentos, placas de carro, recibos e até mesmo imagens manuscritas.
    - c. Acesso aos resultados: O texto extraído pode ser acessado em formato TXT ou JSON. Você pode usar esses dados para diversos fins, como digitalização de documentos, automação de processos, tradução de idiomas e muito mais.
- Insights e Possibilidades: Este serviço é uma ótima ferramenta para aprender sobre processamento de linguagem natural e visão computacional. Você pode usar a API para criar seus próprios projetos de OCR, como um aplicativo de digitalização de documentos ou um sistema de tradução de idiomas baseado em imagens.

*Extract text from images*
![advert](./prints/Screenshot%202024-02-08%20161152.png)
![letter](./prints/Screenshot%202024-02-08%20161415.png)
![note](./prints/Screenshot%202024-02-08%20161506.png)

3. Adicionar Legendas a Imagens:
- Processo:
    - a. Upload da imagem: Carregue a imagem que você deseja legendar para o serviço Visão de IA do Azure.
    - b. Análise de imagem: O serviço usa IA para analisar a imagem e gerar uma descrição textual. A descrição inclui informações sobre os objetos presentes na imagem, a cena e a ação principal.
    - c. Acesso à legenda: A legenda gerada pode ser acessada em formato JSON. Você pode usar essa legenda para melhorar a acessibilidade do seu aplicativo, fornecer informações adicionais para seus usuários ou gerar conteúdo descritivo para imagens em redes sociais.
- Insights e Possibilidades: Este serviço é uma ótima ferramenta para aprender sobre IA e processamento de linguagem natural. Você pode usar a API para criar seus próprios projetos de geração de legendas, como um sistema de descrição de imagens para pessoas com deficiência visual ou um aplicativo de criação de captions para Instagram.

*Add captions to images*
![Ratel](./prints/Screenshot%202024-02-08%20155111.png)
![store-camera-3](./prints/Screenshot%202024-02-08%20160425.png)
![store-camera-4](./prints/Screenshot%202024-02-08%20160458.png)