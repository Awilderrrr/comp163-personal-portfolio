# comp163-personal-portfolio
# Personal Information Storage
full_name = "Ashlyn Wilder"
student_email = "awilder@ncat.edu"
hometown = "Atlanta, GA"
graduation_semester = "Spring 2028"
major = "Computer Science"


# Academic Data Organization(lists)
current_courses = ["COMP 163", "MATH 132", "SPCH 250", "HIS 207"]
completed_courses = ["Biology", "Chemistry", "Calculus I", "World History"]
credit_hours = [3, 3, 3, 3]
gpa_history = [3.2, 3.6, 3.4, 3.7]

# Contact Information Storage(tuples)
emergency_contact = ("Mom", "Leia Wilder", "704-555-0199")
home_address = ("456 Oak Street", "Charlotte", "NC", "28202")
instagram_info = ("Instagram", "@awilder_2", 500)
twitter_info = ("Twitter", "@awilder_2", 123)
birthday = ("Birthday", 01, 22, 2005)


# Interest Tracking(sets)
current_skills = {"Python basics", "HTML", "Problem solving", "Time management"}
skills_to_learn = {"JavaScript", "Data structures", "Git", "Web design", "Public speaking"}
career_interests = {"Software development", "Web development", "Data science", "Cybersecurity"}
hobbies = {"Gaming", "Cooking", "Basketball", "Music"}
entertainment_backlog = {"One Piece", "Barry", "Life", "Incantation", "Memento"}


# Organizational Mapping(Dictionaries)
course_credits = {"COMP 163": 3, "MATH 132": 3, "SPCH 250": 3, "HIS 207": 3}
course_professors = {
    "COMP 163": "Prof. Rhodes",
    "MATH 132": "Dr. Lee",
    "SPCH 250": "Dr. Martinez",
    "HIS 207": "Dr. Brown",
}
course_rooms = {
    "COMP 163": "M-Eric 300",
    "MATH 132": "Marteena 201",
    "SPCH 250": "Crosby 121",
    "HIS 207": "Crosby 210",
}
monthly_budget = {"Food": 450, "Entertainment": 200, "Books": 125, "Transportation": 100}
study_hours = {"Programming": 10, "Math": 8, "Speech": 4, "History": 3}
contact_directory = {"Mom": "704-555-0199", "Roommate": "336-555-7821", "Academic Advisor": "336-334-5000"}


# Required Calculations
total_current_credits = sum(credit_hours)
cumulative_gpa = sum(gpa_history) / len(gpa_history)
completed_courses_count = len(completed_courses)
total_weekly_study_hours = sum(study_hours.values())
academic_load = total_current_credits + total_weekly_study_hours
monthly_budget_total = sum(monthly_budget.values())
daily_food_budget = round(monthly_budget["Food"] / 30, 2)
annual_budget_projection = monthly_budget_total * 12
study_cost_per_hour = round(monthly_budget["Books"] / total_weekly_study_hours, 2)

# Analytics Calculations
total_followers = instagram_info[2] + twitter_info[2]
skills_current_count = len(current_skills)
skills_to_learn_count = len(skills_to_learn)
contact_directory_size = len(contact_directory)
entertainment_backlog_count = len(entertainment_backlog)

# Output
print("PERSONAL ACADEMIC & LIFE PORTFOLIO")
print(f"Student: {full_name} | Email: {student_email}")
print(f"From: {hometown} | Graduating: {graduation_semester}")
print(f"Major: {major}")
print("=== ACADEMIC PROFILE ===")
print(f"Current Semester: {total_current_credits} credits across {len(current_courses)} courses")
print(f"Cumulative GPA: {round(cumulative_gpa, 2)}")
print(f"Weekly Study Time: {total_weekly_study_hours} hours")
print(f"Academic Investment: ${study_cost_per_hour} per study hour")
print("Current Courses:")
print(f"{current_courses[0]} - {course_credits['COMP 163']} credits - {course_professors['COMP 163']} - {course_rooms['COMP 163']}")
print(f"{current_courses[1]} - {course_credits['MATH 132']} credits - {course_professors['MATH 132']} - {course_rooms['MATH 132']}")
print(f"{current_courses[2]} - {course_credits['SPCH 250']} credits - {course_professors['SPCH 250']} - {course_rooms['SPCH 250']}")
print(f"{current_courses[3]} - {course_credits['HIS 207']} credits - {course_professors['HIS 207']} - {course_rooms['HIS 207']}")
print("=== PERSONAL DEVELOPMENT ===")
print("Current Skills: {'Time management', 'Photography', 'Problem solving', 'HTML', 'Python basics'}")
print("Learning Goals: {'Data structures', 'Web design', 'JavaScript', 'Git', 'Public speaking'}")
print("Career Interests: {'Software development', 'Game development', 'Web development', 'Data science'}")
print(f"Skills Currently Have: {skills_current_count}")
print(f"Skills Want to Learn: {skills_to_learn_count}")
print("=== FINANCIAL OVERVIEW ===")
print(f"Monthly Budget: ${monthly_budget_total}")
print(f"Food: ${monthly_budget['Food']} (${daily_food_budget}/day)")
print(f"Entertainment: ${monthly_budget['Entertainment']}")
print(f"Books: ${monthly_budget['Books']}")
print(f"Transportation: ${monthly_budget['Transportation']}")
print(f"Annual Projection: ${annual_budget_projection}")
print("=== CONNECTIONS & CONTACTS ===")
print(f"Emergency Contact: {emergency_contact[1]} ({emergency_contact[0]}) - {emergency_contact[2]}")
print(f"Home Address: {home_address[0]}, {home_address[1]}, {home_address[2]} {home_address[3]}")
print(f"Social Media Presence: {total_followers} followers across 2 platforms")
print(f"Key Contacts: {contact_directory_size} people in directory")
print("=== LIFE STATISTICS ===")
print(f"Total Courses Completed: {completed_courses_count}")
print(f"Current Academic Load: {academic_load} weekly commitments")
print(f"Entertainment Backlog: {entertainment_backlog_count} items")
print(f"Current Hobbies: {len(hobbies)} activities")
