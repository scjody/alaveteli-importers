alaveteli-importers
===================

Importers for use with Alaveteli

The list of organizations in Québec that accept access to information requests (La Répertoire) is available in PDF form here:
 http://www.cai.gouv.qc.ca/documents/CAI_liste_resp_acces.pdf
 
The goal of this software is to parse this document into a form that can be used by Alaveteli.

The current script (fix_repertoire) takes a "half way" CSV file produced manually and turns it into a CSV that Alaveteli can import.  I am working on a better script, in Ruby, that works directly with the PDF (and is more robust).
