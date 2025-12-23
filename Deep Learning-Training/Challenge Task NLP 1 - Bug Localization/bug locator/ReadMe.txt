Usage:
java -jar BugLocator [-options] 
where options must include:
-b	indicates the bug information file,the bug information file must be .xml file in the data folder.
-s	indicates the source code directory.
-a	indicates the alpha factor for combining vsmScore and simiScore
-o	indicates the result file,the format of result file is "bug id, relevant source code file,rank(start with 0),score".

for example the command may be "java -jar BugLocator -b E:\Data&Tool\data\SWTBugRepository.xml -s E:\Data&Tool\swt-3.1\src -a 0.2 -o E:\Data&Tool\output.txt" for SWT system
