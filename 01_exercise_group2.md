[🏠 ](https://github.com/FUB-HCC/hcds-summer-2022/wiki)&nbsp;
[:arrow_backward: Wiki Home](https://github.com/FUB-HCC/hcds-summer-2022/wiki)
:white_circle:
[02 | Exercise :arrow_forward:](../wiki/02_exercise)

# 01 | Exercise - Warm Up
`26.04.22`

In this session we will introduce mainly organizational aspects: the schedule of the semester, upcoming assignments, and the tools we will use during the course. We will look into a small data science exercise together.

## Agenda
- 10:15 - 10:35: Introduction, Exercise overview, and concept
- 10:35 - 10:50: Get-to-know and group forming
- 10:50 - 11:00: Setting up groups rules
- 11:00 - 11:05: __Short break__
- 11:05 - 11:15: First assignment introduction
- 11:15 - 11:40: Early start on the assignment with assistance
- 11:40 - 11:45: Goodbye and outlook

## Session notes
[Slides for first exercise](https://github.com/FUB-HCC/hcds-summer-2022/blob/main/exercise/HCDS22_Exercise-01.pdf).

## Assignment
An assignment usually consists of a programming part `Ax` and a reflection part `Ry`, so does this first assignment. 

If you are unsure how to set everything up, or don't know how to open a jupyter notebook, please check out the wiki's [tools page](https://github.com/FUB-HCC/hcds-summer-2022/wiki/00_tools).

### `A1` - Warm up **[1 point]**
🕐 &nbsp; **Due: Tue, 2022-05-10 10:00 AM**

We will have a folder for each programming assignment in the code section of this repository. --> https://github.com/FUB-HCC/hcds-summer-2022/tree/main/assignments --> `A1_R1_WarmUp`. Each group will create a subfolder for each assignment, named after their group name. For this assignment, each student will put their code into their own subfolder inside the group folder. This folder should be named using your **fi**rst name & **la**st name initials e.g. `fila`.

1. Create your group subfolder in `hcds-summer-2022/assignments/A1_R1_WarmUp/` with your group name.
1. Write down your group norms in a markdown file called `norms.md` and push it into your group folder.
1. Inside the group folder create a folder using your initials, as described above.
1. Copy the exercise file `A1_WarmUp.ipynb` from `A1_R1_WarmUp` into your own folder. 
1. Step through the notebook and do each ✏️ `hands on` section.
1. Push your final notebook.
1. Submit your group's commit hash to `Exercise Programming Assignment 1` in Whiteboard. 

> :exclamation: **Note**: The last step of adding you group's commit hash to Whiteboard is new.

The resulting paths for you files should look like this: 
- `hcds-summer-2022/assignments/A1_R1_WarmUp/GROUP/norms.md`
- `hcds-summer-2022/assignments/A1_R1_WarmUp/GROUP/INITIALS/AI_WarmUp.ipynb`

### `R1` - Reflection **[Optional]**

> :exclamation: **Note**: Writing this reflection is not mandatory anymore. This is also something different than the lecture reflection assignment (which is mandatory). Please check the announcement in Whiteboard!


We will keep track of each reflection inside a CSV file. Why do we do this? We want to have the reflection in a machine-readable format, so that we are able to analyze them later systematically. The CSV file for this assignment can be found under: `hcds-summer-2022/assignments/A1_R1_WarmUp/reflection_1.csv`.

The file consists of five columns. Here is a description of the column's content:
- **Topic**: The topic you should reflect on. Usually, the topics will be given to you, but feel to add more if you would like to. 
- **Reflection**: A reflection written on the topic. Feel free to write as much as you want.
- **Rating**: An number from 1 to 10 representing how well you liked the topic, with 1 being a **strong dislike** and 10 a **strong like**.
- **Questions**: What is still unclear about the topic, or other questions you would like to ask related to the topic.
- **Feedback**: What feedback would you give to the way the topic was covered during the course.

Here is an example for a potential row in your reflection:
| **Topic** | **Reflection** | **Rating** | **Questions** | **Feedback** |
|-----------|----------------|------------|---------------|--------------|
| Writing an example | By writing an example down I better understood how this process must feel to a student. | 8 | Will this example be enough? | Writing it directly in markdown is cumbersome. |

1. Copy the reflection CSV file to your personal folder you created in `A1`.
2. Reflect on the topics you find in the file and fill in the missing columns. Feel free to add more rows to your file.
3. Push your edited reflection file.

#### Editing a CSV file
You can simply use your favorite text editor to enter your writing between the commas. Alternatively, you can use an extension like [Edit csv](https://github.com/janisdd/vscode-edit-csv) for your editor, or use a spreadsheet program like Excel.
- It may be easier to write your reflections somewhere else and then copy the content inside the CSV file.
- If you use commas in your writing, make sure to properly escape them like this `","`, so that they are not treated as a separator.
- You may also use a different separator if you so desire, e.g. semicolons or tabs.  
