# Yuan

a gpt-2 model that can do speech-to-text and back again

the process flow would go like this:

```mermaid
graph TD
A[Human Voice] --|Speech-to-Text model|> B[text]
B --||> C[GPT-2] --|Text-to-Speech model|> D[Speaker]
```