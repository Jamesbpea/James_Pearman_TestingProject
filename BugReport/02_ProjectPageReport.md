
## Summary (Summarize the bug encountered concisely)

Typo detected in the Create new project page 
instead of blank = black

## Steps to reproduce     

Navigate to  https://gitlab.com/projects/new#blank_project
   

## What is the current bug behavior?

Displaying the wrong name for the link
instead of blank = black

## What is the expected correct behavior?
instead of black = blank
should show Create blank project

     
## Relevant logs and/or screenshots

      <a href="#blank_project" data-testid="panel-link" data-qa-panel-name="blank_project" class="new-namespace-panel gl-display-flex gl-flex-shrink-0 gl-flex-direction-column gl-lg-flex-direction-row gl-align-items-center gl-rounded-base gl-border-gray-100 gl-border-solid gl-border-1 gl-w-full gl-py-6 gl-px-3 gl-hover-text-decoration-none!"><div class="new-namespace-panel-illustration gl-display-flex gl-flex-shrink-0 gl-justify-content-center"><img aria-hidden="" src="/assets/webpack/project-create-new-sm.d02514e7.svg"></div> <div class="gl-pl-4"><h3 class="gl-font-size-h2 gl-reset-color">
            Create blank project
          </h3> <p class="gl-text-gray-900">
            Create a blank project to store your files, plan your work, and collaborate on code, among other things.
          </p></div></a>

## Possible fixes

change black = blank

## Whom do you report/ Assign To/ Tags



## Priority

      
High