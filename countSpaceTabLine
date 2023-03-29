/* Write a program that counts spaces, tabs and new lines */

#include <stdio.h>

    main() {
        int count;
        int spaces, tabs, newLines;
        spaces = tabs = newLines = 0;
        
        while ((c = getchar()) != EOF) {
            if (c == ' ')
                spaces++;
            if (c == '\t')
                tabs++;
            if (c == '\n')
                newLines++;
        }
        
        printf("------------------------------------------\n");
        printf("Total spaces: \t%d\n", spaces);
        printf("Total Tabs: \t%d\n", tabs);
        printf("Total new lines: \t%d\n", newLines);

}
