# Excel-To-Statistics

pip install pyexcel-xls
pip install pyexcel-xlsx
pip install pyexcel-ods
pip install -r requirements.txt

You will need to update your settings.py:

FILE_UPLOAD_HANDLERS = ("django_excel.ExcelMemoryFileUploadHandler",
                        "django_excel.TemporaryExcelFileUploadHandler")
