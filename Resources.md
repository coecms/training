Before you go ahead:
my overall feeling is that like for all our documents the granularity is a bit unclear.
For example in Project there's some really minor steps while the first point of Monitor include a lot of commands.
I've outlined below a few suggestions also indicating what I think are prerequisites #pq or there might be an overlap -> 
It's just an example to explain what I think might be a more even granularity rather then a comment on content. 

### Project

 * Determining appropriate CLEX project code,
 * Contact project coordinator (CI or delegate)
 * Request to join a project through mancini  #pq
 * Determining CI of project, #pq? (I'm thinking either via mancini, so potentially redundant or via wiki since mancini might not have enough "scientific" info)

### Resource request

 * Determining resources required, e.g. running model, analysing data
    - Compute resources (KSU)
    - Storage resources (GB): short term (`/short`), medium term (`/gdata`) and archive (`mdss`)
 * Determining project allocation (`nci_account`) #pq
 * Contact project coordinator with resource request # (isn't a bit redudant? they should have started a dialogue already)

### Monitor resource use

 * Check resource use NCI tools:
           ** nci_account, 
           ** <fsystem>_files_report
           ** lquota
 * Extra tools for Clex projects:
           ** nci_monitor
 * Useful bash commands ( `du`, `ncdu`, `find`) -> bash basics?

### Managing storage
 * NCI filesystems and their correct use #pq?
 * managing file ownership and permissions:
    * chmod, chgrp -> bash basics
    * acls
 *  compress: 
    ** nccompress
    ** cdo and nco -> ??
    ** gzip, zip, bzip etc. -> bash basics?
 *  delete ? maybe we can skip this? (`find`, `rm`) -> bash_basics
 *  transfer:
    ** across filesystems -> bash basics? (I'm thinking of difference between cp and mv and what happens to permisisons etc.)
    ** from/to remote server (rsync, scp, sftp) -> NCI user guide 
 *  archive data ( `tar`, `mdss`, `mdssdiff`) -> NCI userguide (for mdss)
