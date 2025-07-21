# Sistema de Controle de Estacionamento para Hotéis

> Projeto desenvolvido como solução de mensageria para o controle de entrada e saída de veículos em hotéis.  
> Feito com Laravel. O código-fonte completo está disponível em outro repositório.

---

## Sobre o Projeto

Este sistema foi criado para facilitar a operação de mensageiros/manobristas em hotéis, otimizando o registro, consulta e gerenciamento de veículos em tempo real. A aplicação centraliza informações relevantes para auditoria e operação, além de garantir segurança e rastreabilidade dos dados.

---

## Funcionalidades

### 1. Autenticação
- Sistema de cadastro e login com autenticação segura.

### 2. Dashboard
- Visão geral das operações recentes.

### 3. Check-in de Veículos
- Registro de veículos com os seguintes dados:
  - Mensageiro responsável
  - Nome do hóspede
  - Modelo, cor e placa do carro
  - Número do apartamento
  - Número da credencial
  - Observações gerais
  - Localização da chave (gaveta, balcão ou com o hóspede)
  - Checkbox para sinalizar se o hóspede entrou direto (sem dados)

### 4. Consulta de Veículo
- Busca rápida pelo número do apartamento.
- Exibe os dados do veículo mais recente em check-in.

### 5. Histórico de Veículos
- Tabela completa com todos os registros de check-in e checkout.
- Exportação em PDF para fins de auditoria.
- Edição de registros para atualizar dados em caso de mudanças (ex: troca de chave ou apartamento).

### 6. Checkout de Veículos
- Listagem de todos os veículos em check-in com botão de checkout individual.

### 7. Gerenciamento de Mensageiros
- Área restrita apenas à gerência.
- Cadastro e administração de mensageiros/manobristas.

---

## Imagens do Sistema

### Tela de Check-in
![Tela de Check-in](caminho/para/imagem-checkin.png)
<img href="https://lh3.googleusercontent.com/fife/ALs6j_Ej7cr3uiIK0s6Hu0vwqvXa4rSwYpVtdW6kXGOGxWOz1gnlbl_BUIzR7KTphpyR6l6JW-vP6BoxafWcz9uSN1Xk9qdcYntywskS0c6nV5nA892UfBzDjqJb0OetwnN76Z2l7LCEOyayP6geoUum23GZaat3LOhPrF-oocujFPpuR_hF7oCXAue682lxOhfywVkizk9UbmsnNzmllyR4qlIEdYiIkq9e4hFhxSywSr2G_X1qwHmMoyc7t0Pt9z7pqhyarM7HsDk8nE2EczQ3U3MpbgAguCf9pHIEuYzkCm9JWog5NyE29BuPP0JperxMeymwVtvTV8K3aP1AoZIOOxssHZvoKFiE0fDsg5fFj_0Qt3wI2eNVWfFfrrdA3dTOqyT1Xfnef4QtBnNDYpxzQahDKtcY_Zqw49pY3R4bWVWY7K5APkp7lNqFQTvXodVkjvASbRlpkieQiPgb619Cfkj1DFnXhtudYdiYdNuEmUzaPCaulp6UmrMid-PZlakRyGObwi8Og5wGLhAh76AdEotqSvKMMIvH-2A49BwkrgJ39GIOP9_uK0Z2TE4iPFUf8HzNtDshI2drZCD4Uj9t4X_sXTeo_2T954WcO9rXB1qUSw9Pk2p6vLO__CtubmxjJAK81APraLd7hwolTEhUea2YJ_SJDjNzI8VFB-YskvkSMuzfSyzlhxtCBBJtBI5f2TKp_iG5sjmQefCPoN8BjCT1R1ubv6zQHJmT0-2XnlXIkCW6U1r12I4V4Y3nq9M331cgP6HFTr4ocNhV3pNrZ0U00qwYIFILz0w6pWjBDs9vAWvQidhzAQb4KPMN4m5vav0u6VYkwabe_jjc-nEhuB5GtDtzp3RioNKFfjSoY07gXbt1YqHuuEjej3wFQ8MAFGB2cujLzi-m-KEO0PzcoEomTxyhnZVc0ZE3vOIj32m-clZCMab-ZOg3O4s40JDGWOxxBs6NYEDFtZ7M5lVYNxoASvpu1RWf6x0ZzzCsqFsFsHSOTTfxclLfL7cvN7FJ13N0Og7CGnRJ7r3ecvWAF9Ky2iLooOqzRZg1VXKbV9FsViR7DKieSSMbMGMSkip4q-pmkJCVGrofSO9fmS6JV7mon6lSEKIWgKthheGjcCnr41RyFbDaJ1h1zhr395rXs5Zv-9Wz0FvYcWXI1E-wKS-Ujs0cmVpUPe9ovA1DTwVpadbYVARLb-1ZjaXYM1e357TmbXRoDFoL2RLkaAjG2MDJ639zPJqBjtpeV5ElVQPlQT0p1HGFaC1wUEyg6Tc3WB9zuMwaJp0SOx5v11VU26lX-8zRfjSmkiEJs5vf0TIkTV1zOYFFaFIqOr7eqia6DIF3Ws_wmBQnevG1aGw5rtIqDpf8SiPaV7G51xmGNPgg3UVcYJ0jqzISSYgmTCe6o2Aa7IV-3P81LrKAc_GoFuWHGbIpPZkXmO757VVB58MXQZylO5kdyDwtteRN2ls-sszVPb4aPGIM6hSDEfI8PkXx3BWRMiOw7GzzU7V1ZhCTx542BLlkpylCwVfIrUwPfl-3zo5fleWLTuh92CRTzooTwMn33roYVKPkOAiJuarffGXE5yT8ARHEVszr1l8grLDeWK-AG1VrTLqUw3A0HIEHZmRCRX0FOYu-CA=w1115-h607?auditContext=forDisplay">

### Histórico de Veículos
![Histórico de Veículos]
<img href="https://lh3.googleusercontent.com/fife/ALs6j_E5vf8lZe5meQn8GoS4AefqvxuEnDgA2MLzcP2qzElxV0N9crr0fQWxoqzH0cvOJ10Ew0ufbXAoCSE4z9hSYs5sN1zVbMyPQxJFnthbszE814UuVSUDLcVpjgH1h2tTEUvL3Ov1ElCjOWcOWXiNvNcqlAp0_G0ICoxqb6HpQ8RuGs6drRld_CX5ghJt0ghGe4sxgGPQEiWKoLx8cOcoDNg5sSPaTCi8ZFXDU3K7bSJdcwFVyMcbZcc6UlE0bkQke34jSWLVFm9yY1PY15kCKPuojW8JQBPcs69QuZBLy76ibBIuRbS5Tpb2EfePnbkts1rsZuTP8DyikPsE76lPiTdlRXYupqgiKPMKqveHuRm3acdBsNdfjbSKMTrZBbp3mpWE5eWEkVRVsPjBXdqAlPAgIro6M26rg2a-tS3QvLr8QktcDQIwNQgPJlD86NtaHpZdiktH_XTVMupMPlijF4nL5lCxVh64c9S8nCpKPThDPL4_rSljmDVFo_jgzD_-GfsfuFW8Db-EZkWpE-oZY6VxMdfqfB2qnShFHKyY54n6SnrSwh5-8zEdLiaY7cQ-Y8lTzTlxgxBS-zhvZurTrHCpjc_RHLJxhWf6LuV8dCVrDYMbBptzuGVG_1XTLXopStN5tNSmxqkD3VfCijRL2fU4L11pzeM9c82Uvz0qAHv9HZETkcIJPM-w9j9GYSjGrxgJOM4Xg3TYzJX4ZdfSKxEdkVv985S8R3Xx2WB2-S22BiakALOx6CXagWvoHPQ2U8HwE9BeI9UR1kyqlqGvi4oNw-Ny3ro97MAXyS0sYTe1W06mr75KiiY6An1qquabMupPrfolODZEBvHFXJduxuPZFIjMyVnL5Dn_rODgmbEs82XsrtYisU8oAqIheOXss2j3f9NGGQ0ZnqoVfD9zKI2Aqbhb20l90S9qwTOeD_oz8KZc9i5vkR1M5C5rWbMFOaxj29B0L3Zk5gHA2Bd61qVszMN9iKbBYTluEVV-VP8gibKWEyyvd5FPtQuLb_WJ3TfGzC42BfbQyOengxiBHIUkUdMmu1NQGK3OAp4GaOVyiDwMie380iWZ0goKzrM71q-N9BBB6-4WTYBtV_R5HOMyzOAvjHYkNSonE2x1eg9rCXCt_PBh908UqIGtUIrXLSs_eZQkPpgrdtj_4DTtAVM8AR4DBtibRF_7EL25545QNrXlkMH2q7y01I-V3Uq8-79AUHnhilP8x95EVXvmRQSlo8sdy0K_MvFqQsZfWEFQBsW0Gb4ZF9cqoki4gTi23FXGvmrpXpNNK1DfSFD6nYPWMGazbA6RUZ1SgN-ecR0Z6ZnFpGy-i4sdWKojhmLh6j65Ck8HFOaI15Yz8uAW7Nfaznuc2tioQqMuZcNAGSDarBtwPPUOrPQAH7tkZjfBrg30yIydOyofbDoTVJzV3opf0gj7rCISTqWV3mll_PWNxHcqOd7WBtim6j5QjGXgkjAgpVFGu70X6bMGT2skPf2mWckmBjHBel41i_AoN9PcHaeLjZblKU99rsb3E1lYGOzoEB_dzSgcoBaXjCFvzBklM0Zk5StSW_w5kQuxJicZtN45inHtkjoB1rE9npyLUi0qRD-eE3AQEc7TwQQgJRgvDBrblHwjFgBVxQ=w1115-h607?auditContext=prefetch">

### Checkout
![Checkout]
<img href="https://lh3.googleusercontent.com/fife/ALs6j_GUKb4222qm1aJO1bLE1Kmw2_hBWQRQxObkU2C96t9ObcHqge1eV_e-JbUYMk26LjAjhhMLSktW7RHexTxDFu3T4T5SRosNPE5BqhQjjE0jXCenU6EEF9uQAVIxGa2rw6Wsk17JiqkIXbh-Ky4x_Zq1lLHS7Oz7_KhNA_JcuGXofgf_bW8GvNXqC196smU1JZWLLnmdi64C6Q_qqUTTuH904hn_GDpxoAJDicmYAzIdLaxFC7WrV2-xAnM7hH1bKh1I_s9OFM4h73oAXpHgsY7Ja-i_XAHUxwj0r8TxAdeCGkzTP9Xmb-VPLlmQ4F8zaywyFnt16HT3wTo4GuD1_835_SZVZRZyfDjtkB9BDErU_1fNzGB0Dqnz22Bi-GYwksNUTP-PltVU22lZKSXLVB7KOLm7F3PNznWRKtpL-AuqbXqDGZaXz19ETSb94Ug6SvIbfe_-cJPOnS2jD-XefAmo3_cfgyIvWGeY6mNYBMlZVxXv7wrEGb-0HFq1-q_8My1rajbbXUA65BXGfbS1eQdgoQgphraZN7f2Ap1eBCCfAKNqnWW7PBOvVnjogQcckoUzT44jx6u1IuKv_M8kTpNXEpdildkLLjNNXDdyukRLeKOYFiGLOS6T7CaR4LZN4qoMhNoMpRw2-6Ok3ntOXji1Xt564kp4AL2eqS2S5xkiMSefwXaHwJzPCkMcx7Dr4dct1uxc617uR4auK0hZq_Q_nXabDvkpNFtyHoCb9qMZ8QuKUJ4AgrPq4mBw6PpF_XP7LcfLQiPPtWk9VFsPO_49h0eUGYdOSyy97cVUXo1gS5uKpKrmdMxa3RN2YUBSveHs4sPchCOhwT6xz6Wk5et3IsA_uUpVz8LtlR1RLOIeAdEmVOLLXmMomE1lOPPVvLt5CstHN48ELlxbuppVTal7EtIjg07hdqwRDmI2lxasoq173rF0-zoIIUsJKWoQwICXiV053b-RMvx1tV0zh6v_5qOgElNH00o4G-bY2MKnS5zpCoqn1912EjIJEGrAsCqRHxazem42IxyyjEjphI26En4rtm7zXzaNhOxfUOaXESjBo6sun68J-lix3xksN9Mt6PUDQ3VN0kudAGvFmbRjpoMQKJivEgvn2JEhxfkwgs17DuHUmN8EiFV4M29Lh14z8-lWvasZf-BwNdDewmYGEodkX0YqSsuKyiV41FR0LBjmQDmC3doOkQ5nz5m1iSsPD9MHT9dfsm-0j38_B9Plpw-SeXM2ZXp2J9t-gfuwQEAF7xfOvawMdM9FKlRkaF5Bi98s-vUDZQ5QGn48u4r8H8GylOBiu-5pvnGNwnELxhITkqJLDnN8bgjFc_kjhdbfNqmLgqN7JiJGeAHlYh5Gx4wO03-VK8z1HRZ8U2HmzrooMLARRggW1o4hlfEcII0uvkoKZiyTEqtA7DzP9LTVoQOqIaY2ff96MXvuioMMswI1ZoarU6hcQvmHUA57loTrh82ImYPf6eAkcO-a99ROlpZAjylxuBLhfmmVYyuMVKpFFFYWri012nbbuBkdfuwgJOKH4uY0YD-Co-AWtMXhf3Ufr6gcQGVMLeS8QNWPwA8yW1kWaOXinmxj9SWE0CK86QXxPLdOT2DiTXtuLL7OS4JJpj52mDRTFg=w1115-h607?auditContext=prefetch">

---

## Tecnologias Utilizadas

- Laravel (PHP)
- Blade Templates
- MySQL
- Tailwind
- DomPDF (para exportação em PDF)

---

## Autor

**Desenvolvido por mim**  
Dev formado em Análise e Desenvolvimento de Sistemas   

---

## 📬 Contato

Fique à vontade para entrar em contato caso tenha dúvidas, sugestões ou oportunidades.

---

