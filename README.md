# knowledge-graph-product-classification
Knowledge graph for product classification and recommendation using OWL, RDF, and SPARQL with semantic reasoning.
# 🛍️ Product Knowledge Graph – Classification & Recommendation System

## 📌 Project Overview
This project builds a knowledge graph to model products and automatically classify them using semantic reasoning.

The system uses OWL ontology and RDF data to represent product attributes and relationships, and SPARQL queries to retrieve recommendations.

## 🎯 Objectives
- Structure product data using a knowledge graph
- Apply rule-based reasoning for classification
- Simulate a recommendation system using SPARQL

## 🧠 Key Features
- Automatic classification (e.g., Vegan, Premium)
- Semantic relationships between products and attributes
- Query-based recommendation system

## 🛠️ Technologies
- OWL / RDF
- Protégé
- SPARQL

## 📂 Structure
- ontology/ → product ontology
- data/ → RDF dataset
- queries/ → recommendation queries

## 🤖 AI Logic
The system infers product categories based on logical rules:
- Products without animal ingredients → Vegan
- High price products → Premium

## 🔍 Example Query

```sparql
SELECT ?product
WHERE {
  ?product :isSuitableFor :Vegan .
}
