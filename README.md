# Traduzir
Teste com codigo para traducao

print(json.dumps(
    language_translator.translate('Hola, cómo estás? €', source='es',
                                  target='en'), indent=2,
    ensure_ascii=False))
print(json.dumps(language_translator.translate('Hola, cómo estás? €', source='es', target='en'), indent=2, ensure_ascii=False))
