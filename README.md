# Desconto Sustentável (Admin API)

A API do aplicativo Desconto Sustentável permite a exclusão de usuários pelo administrador. O aplicativo Desconto Sustentável é uma plataforma focada em reduzir o desperdício de alimentos, oferecendo produtos alimentícios com desconto e próximos da data de validade. O serviço conecta consumidores com varejistas e produtores que têm itens alimentícios que precisam ser vendidos rapidamente. Os usuários podem encontrar uma grande variedade de produtos, como mantimentos, refeições prontas e muito mais, todos com preços reduzidos devido à proximidade da data de validade. Esta iniciativa ajuda tanto o meio ambiente, minimizando o desperdício de alimentos, quanto os consumidores, fornecendo produtos acessíveis e de qualidade.

## Tecnologia

API criada com express. O banco de dados utilizado é o Firebase Cloud Firestore.

## Configuração

- Instale o NodeJS;<br/>

- Instale as dependências com o comando "npm install" no diretório do projeto;<br/>

- Crie um arquivo .env na pasta raíz do projeto e adicione as variáveis de conexão do Firebase ao arquivo, como no exemplo abaixo:
```
# Conta de serviço do Firebase
FIREBASE_PROJECT_ID="random-project-id-12345"
FIREBASE_PRIVATE_KEY_ID="b8d4c8f1d3a8b0f1f6c8b7a8e5f1f0c5d4c8e1b6"
FIREBASE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\nMIIEvgIBADcxmfQieKb6izaeuTVZib3IxmQwJE6l/cTk+5rL+T5X\nR6YWj01Qdpv8Ywt22yA3bTC/\n-----END PRIVATE KEY-----\n"
FIREBASE_CLIENT_EMAIL="firebase-adminsdk-random@mkt-alimentos-random.iam.gserviceaccount.com"
FIREBASE_CLIENT_ID="123456789012345678901"
FIREBASE_AUTH_URI="https://accounts.google.com/o/oauth2/auth"
FIREBASE_TOKEN_URI="https://oauth2.googleapis.com/token"
FIREBASE_AUTH_PROVIDER_X509_CERT_URL="https://www.googleapis.com/oauth2/v1/certs"
FIREBASE_CLIENT_X509_CERT_URL="https://www.googleapis.com/robot/v1/metadata/x509/firebase-adminsdk-random%40mkt-alimentos-random.iam.gserviceaccount.com"
FIREBASE_UNIVERSE_DOMAIN="googleapis.com"

# Variáveis do App Firebase
VITE_FIREBASE_API_KEY = "AIzaSy1234567890abcdefgHIJKLMNOPQRST"
VITE_FIREBASE_AUTH_DOMAIN = "exemplo-app.firebaseapp.com"
VITE_FIREBASE_PROJECT_ID = "exemplo-app"
VITE_FIREBASE_STORAGE_BUCKET = "exemplo-app.firebasestorage.app"
VITE_FIREBASE_MESSAGING_SENDER_ID = "123456789012"
VITE_FIREBASE_APP_ID = "1:123456789012:web:abcdef1234567890abcdef"
```
As variáveis da conta de serviço são necessárias para o uso do firebase-admin e podem ser conseguidas pelo site, nas configurações do projeto -> contas de serviço -> SDK Admin do Firebase -> Gerar nova chave privada. As variáveis do App também podem ser obtidas nas configurações do projeto, mas na aba Geral, em "Apps da Web".<br/>

- Utilize "npm start" para iniciar a API no modo desenvolvimento.

## Rotas disponíveis

* /api/users

## Autores

- José Robson Cabral (Aluno do PPGASA);<br/>

- Paulo Rogério Barbosa (Orientador);<br/>

- Matheus Pedrosa Souza (Desenvolvedor do sistema);<br/>

- Mozart de Melo Alves (Coordenador do núcleo de pesquisa).