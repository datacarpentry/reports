report: Moore_DataCarpentry_progress_report.pdf
responses: Data_Carpentry_responses.pdf

Moore_DataCarpentry_progress_report.pdf: Moore_DataCarpentry_progress_report.md format.sty
	pandoc -H format.sty -V fontsize=11pt Moore_DataCarpentry_progress_report.md -o Moore_DataCarpentry_progress_report.pdf

Data_Carpentry_responses.pdf: responses.md format.sty 
	pandoc -H format.sty -V fontsize=11p responses.md -o Data_Carpentry_responses.pdf