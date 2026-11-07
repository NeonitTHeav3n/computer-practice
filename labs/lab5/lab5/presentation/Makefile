# Сборка презентации ЛР №5 (нужен Quarto)
all: presentation.pptx

presentation.pptx: presentation.qmd
	quarto render presentation.qmd --to pptx

clean:
	rm -f presentation.pptx
