Three "Must" alterations settings.py / base settings to add custom templates along with static directory:

1. Add STATICFILES_DIRS = os.path.join(BASE_DIR, "static")

2. Add the project name as entry to the INSTALLED_APPS list

3. Set the DIRS entry inside TEMPLATES to [os.path.join(BASE_DIR, "templates")]

4. COMPANY_NAME , add context_processor.py as shown and then also update the entry in 'context_processors' entry inside OPTIONS inside TEMPLATES