# ADR-004 — React Native (Mobile-First)

**Data**: 2026-06-12
**Status**: ✅ Aceita
**Autor**: Elir

## Contexto

O projeto precisa ser acessível tanto em desktop quanto em mobile. A decisão é entre desenvolver uma PWA web-first ou uma aplicação mobile-first com React Native.

## Decisão

Aplicação **mobile-first** utilizando **React Native**.

## Motivação

- **Um único código para Android e iOS**: Reduz drasticamente o esforço de desenvolvimento
- **Menor tempo de desenvolvimento**: Reaproveitamento de componentes e lógica entre plataformas

## Observações

> **Nota da equipe**: O frontend web (React + Vite) permanece como parte do MVP para o Demo Day do hackathon. O React Native é uma decisão estratégica para evolução futura, com possibilidade de compartilhar lógica de negócio entre web e mobile.

## Consequências

### Positivas
- Cobertura mobile nativa (Android + iOS) com um único codebase
- Experiência do usuário mobile superior a uma PWA
- Compartilhamento de lógica com o frontend web (TypeScript)

### Negativas
- Requer setup adicional (Expo/React Native CLI)
- Pode não ser prioridade para o MVP do hackathon
