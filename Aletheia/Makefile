SRC_DIR := src
TEX_FILE := $(SRC_DIR)/main.tex
PDF_FILE := $(SRC_DIR)/main.pdf

LATEX := pdflatex

all: $(PDF_FILE)

$(PDF_FILE): $(TEX_FILE)
	$(LATEX) -output-directory=$(SRC_DIR) $(TEX_FILE)

clean:
	rm -f $(SRC_DIR)/*.aux $(SRC_DIR)/*.log $(SRC_DIR)/*.out $(PDF_FILE)

.PHONY: all clean

