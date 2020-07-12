



<h1> Esta é uma linha de código em HTML.</h1>


{% extends "base.html" %}

{% block title %}{{ SITENAME }} - {{ tag }}{% endblock %}

{% block content %}
    <main>
        <section id="list">
            <h2>#{{ tag }}</h2>
            <ul>
                {% for article in dates %}
                    <li>
                        <a href="{{ SITEURL }}/{{ article.url }}">{{ article.title }}</a>
                        <time>{{ article.date|strftime('%b %Y') }}</time>
                    </li>
                {% endfor %}
            </ul>
        </section>
    </main>
{% endblock %}




# **Apresentação Github**

### Durante meus estudos e minha carreira construí materiais que gostaria de compartilhar com todos. Separo por temas e conforme eles foram construídos

### Veja meu CV completo

## **Gestão da Qualidade**
SGQ e Auditorias
Metrologia com IOT (IBM Watson e NodeJS)
Qualidade em treinamentos e geração de competências

## **Gestão por Processos**
Processos ponta a ponta (E2E)

## **Governança TI**
Estudos em COBIT e certificação]
Estudos ITIL e certificação
Metodologia Ágil

## **GRC (Governance, Risk and Compliance)**
Controle de licenças e acessos


