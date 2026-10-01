---
tags: [aws, ai-practitioner, modulo1]
---

# Lesson 1 - Fundamentals of ML and AI


## EN original (core)
> Artificial Intelligence is the field that enables machines to mimic human intelligence. Machine Learning is a subset of AI that uses data to learn. Deep Learning uses neural networks.

## ES mi versión
IA = imitar inteligencia. ML = aprender de datos. DL = redes neuronales.

## Mapa mental
[[AI]] > [[ML]] > [[DL]] > [[GenAI]]
- AI: Rekognition, Polly
- ML: SageMaker
- GenAI: Bedrock

## Vocab AWS
| EN | ES | Ejemplo AWS |
| Artificial Intelligence | inteligencia artificial | Rekognition detecta caras |
| Machine Learning | aprendizaje automático | SageMaker entrena modelos |
| Deep Learning | aprendizaje profundo | redes neuronales |
| Supervised learning | supervisado | predecir precio con labels |
| Unsupervised learning | no supervisado | agrupar clientes |
| Reinforcement learning | refuerzo | agente aprende por premio/castigo |
| Labeled data | datos etiquetados | fotos gato/perro |
| Inference | inferencia | usar modelo en Bedrock |
| Training vs Inference | entrenar vs usar | SageMaker entrena, endpoint infiere |

## Feynman - Explícalo
ML es como enseñar a un niño con ejemplos. Le muestras 100 fotos de gato etiquetadas (training), luego le muestras una nueva y adivina (inference).

---
# Flashcards 

Q::What is the difference between AI, ML and DL?
A::AI > ML > DL. AI mimics human intelligence, ML learns from data, DL uses neural networks.

Q::What is supervised learning? Example AWS?
A::Learns from labeled data. Ex: predict fraud, house price. SageMaker.

Q::What is unsupervised learning? Example?
A::Finds patterns in unlabeled data. Ex: customer segmentation, clustering.

Q::What is reinforcement learning? Example?
A::Agent learns by trial, reward/penalty. Ex: robotics, games, DeepRacer.

Q::Training vs Inference?
A::Training = teach model with data. Inference = use trained model to predict.

Q::What is generative AI?
A::Creates new content (text, image, code) from prompts. Ex: Bedrock, Titan, Claude on Bedrock.

Q::When is ML NOT appropriate?
A::When rules are simple, little data, or need 100% explainability. Use hardcoded logic.

Q::Supervised vs Unsupervised in one line?
A::Supervised has labels, unsupervised finds structure without labels.

Q::What AWS service to build/train custom ML?
A::SageMaker

Q::What AWS service to use foundation models without training?
A::Bedrock

Q::Identify: Rekognition, Polly, Transcribe, Translate are what type?
A::Pre-trained AI services, no ML expertise needed.

## Pregunta tipo examen
Q: A company wants to group customers without labels. Which ML technique?
A: Unsupervised learning - clustering.