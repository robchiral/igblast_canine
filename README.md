# igblast_canine
Canine IGHV data for igblastn. Based on IMGT release 202214-2 (05 April 2022).

Usage:

igblastn \
  -germline_db_V ~/internal_data/dog/dog_V \
  -germline_db_D ~/internal_data/dog/dog_D \
  -germline_db_J ~/internal_data/dog/dog_J \
  -organism dog \
  -auxiliary_data ~/optional_file/dog_gl.aux \
  -domain_system imgt \
  -ig_seqtype Ig \
  -outfmt 19 \
  -query ~/myseq.fasta \
  -out ~/myseq.tsv
