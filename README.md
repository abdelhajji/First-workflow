# First-workflow
on: push                                                  
jobs:                         
  first-job:                           
    name: Say hi                           
    runs-on: ubuntu-latest                           
    steps:                           
    - name: Print a greeting                             
      run: echo Hi from our first workflow!