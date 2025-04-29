# csci322-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSCI322 ASSIGNMENT 1 Solved](https://www.ankitcodinghub.com/product/csci322-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113621&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI322 ASSIGNMENT 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h1>Task 1: User management</h1>
A company has set up a new site and transfer staff and visitor accounts to the new site.

Your task is to write a Bash script to create user accounts for all staff and visitors. The supplied user file Usernames.txt is a text file containing a username and its type delimited by comma per line. There are two types of users: staff and visitor. Staff users are added to the staff group and visitor users to the visitors group.

<ol>
<li>Write a Bash script, called sh, to do the followings.
<ol>
<li>Create two groups called visitors and staff;</li>
<li>Create an account for each user and add the user to its group in one command.</li>
</ol>
</li>
</ol>
All user accounts are created with an initial password the same as their username; a home directory with the same name as their username in the /home directory; all accounts use Bash shell program.

<ol>
<li>Write messages to syslog for all of the above events (new group, new user creation).</li>
</ol>
Note that while the current need is to handle limited number of usernames from the given user file, your script should be

able to handle an arbitrary number of usernames.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(4 marks) </strong>

<ol start="2">
<li>Write a Bash script, called sh, to report the members of visitors group to the file</li>
</ol>
/tmp/visitors.txt.&nbsp;&nbsp; The output should contain the user names only with each user in a separate line.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (<strong>1 mark</strong>)

<ol start="3">
<li>Create a crontab entry to call the sh script at <em>8:00AM</em> and <em>9:00PM</em> on <em>every weekdays</em>. (<strong>1 mark</strong>)</li>
</ol>
<h2>Task 2: Web log analysis</h2>
From the supplied (historical) NASA web server access log (NASA_access_log_Aug95.txt):

<ol>
<li>How many POST events appear in the log? Show the command you use to determine the number.</li>
<li>Write a one-line command to find the last gov GET request for the /history/skylab/flightsummary.txt file. The output should list the fully qualified host name and its time of access. (Don’t worry about removing any square brackets.)</li>
<li>Write a one-line command to compile and print all of the <em>Expendable Launch Vehicle</em> names listed in the log. The ELV names are all listed in capital letters under the /elv Your output should appear in the format of one name per line, with no duplicates:</li>
</ol>
ALICE

BOB

CHARLIE

Save your output in a text file called elv.txt.

<strong>&nbsp;(4 marks)</strong>

<h1>Submission</h1>
Submit individual work as a zip file called a1_yourUserID.zip, containing all your scripts, visitors.txt, elv.txt, and a file answer.pdf containing your answer to Task 1.3 and Task 2 to Moodle submission drop box before the due time. For example, if your user ID is abc123, name the file as a1_abc123.zip.
