# **PASSO A PASSO SIMPLES**

---

## **1) Instale o Git**

Baixe e instale em: [git-scm.com](https://git-scm.com).

---

## **2) Crie o repositório no GitHub**

Crie um repositório vazio e copie a URL (HTTPS).

---

## **3) Abra o Prompt de Comando**

Vá até a pasta do seu projeto:

```bat
cd CAMINHO\DA\PASTA
```

---

## **4) (Opcional) Limpe um Git antigo**

Se existir uma pasta `.git`, apague:

```bat
rd .git /S /Q
```

Se aparecer **“o sistema não pode encontrar o arquivo especificado.”**, siga adiante.

---

## **5) Inicie o Git e faça o primeiro commit**

```bat
git init
```

```bat
git add .
```

```bat
git config --global user.email "carlos.devvv@gmail.com"
```

```bat
git config --global user.name "CodeByCarlos2k01"
```

```bat
git commit -m "first commit"
```

---

## **6) Conecte ao GitHub**
Coloque a URL-DO-SEU-REPOSITORIO após o `origin`.
```bat
git remote add origin 
```

---

## **7) Defina a branch e envie**
Coloque o NOME-DA-BRANCH após o `origin`.
```bat
git push -u origin 
```

---

✅ **Pronto!**
Da próxima vez, basta usar:

```bat
git add .
```
```bat
git commit -m "mensagem"
```
```bat
git push
```
