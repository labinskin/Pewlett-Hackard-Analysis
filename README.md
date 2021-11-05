# Pewlett-Hackard-Analysis

##### Overview:

Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

##### Results:

![](https://github.com/labinskin/Pewlett-Hackard-Analysis/blob/main/retiring_titles_table.png)

- Based on the retiring_titles table above:

  - 29,414 Senior Engineers are retiring
  - 28,254 Senior Staff are retiring
  - 14,222 Engineers are retiring
  - 12,243 Staff are retiring
  - 4,502 Technique Leaders are retiring
  - 1,761 Assistant Engineers are retiring
  - 2 Managers are retiring

  - Adding these together, there are 90,398 total positions eligible for retirement
  - Most notably, there are 45,397 Engineers in total retiring, 40,497 Staff in total retiring, with these two areas being the largest areas and ones with the most replacements needed
  - Only 2 managers are retiring, meaning management is not majorly effected by the silver tsunami

##### Summary:

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?

- ![](https://github.com/labinskin/Pewlett-Hackard-Analysis/blob/main/retiring_titles_table.png)

  - A quick sum of the retirement_titles table reveals that there are 90,398 employees that will be eligible to retire from the company. This is a large section of the workforce at the company and will not be easily replaced.

  - The two largest areas come from senior positions, Staff and Engineer, making these areas hardest hit. With Engineer and Staff being the third and fourth leading titles for retirements respectively. The Staff and Engineer departments are going to be the hardest hit and need the most replacements, with 45,397 Engineers in total retiring, 40,497 Staff in total retiring.

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

  - Adding the Senior Staff and Senior Engineer totals together, there are 57,668 senior level positions retiring (or approximately 64% of the total). This provides a solid qualified based to mentor the next generation. However, there are some reservations.

  ![](https://github.com/labinskin/Pewlett-Hackard-Analysis/blob/main/total_eligible_for_mentorship.png)

  - To get further insight into the mentorship data, I broke it down two different ways. This table shows the total number of those eligible for mentorship from what Bobby's manager requested. That total is 1,549, a mere fraction of the total number retiring or .017% of the total. There are not nearly enough employees in the query run to replace the massive retiring tsunami.

  ![](https://github.com/labinskin/Pewlett-Hackard-Analysis/blob/main/mentorship_breakdown_by_title.png)

  - The second way I broke down the mentorship data was by job title. The good news is that there eligible employees in the Staff and Senior Engineer titles, with fewer being around in the Engineer and Senior Staff positions.

A few concluding thoughts and recommendations. First, the small fraction of employees that are eligible for mentorship does not mean that they are ideal candidates. Some of those employees might not be senior level quality. And, even if they all are, they are a mere fraction of the total needed to replace the coming "silver tsunami." The retirement eligible pool was over three years, for those born from 1952-1955, while the mentorship eligible pool was only for those born in 1965. It might be wise to expand the pool of those eligible from 1965-1968 or even larger if needed to replace the massive retirement wave forthcoming. Second, management might want to stagger retirement offers and packages over a three year period to slow this "tsunami" from being a one time event to a slow wave, with waves of retirements and mentors replacing them. As noted there are plenty of mentors available, but not as many mentees. This would also give time for younger generations, outside even an expanded 1965-68 range to rise to the position of being eligible for mentorship and a move upward.
