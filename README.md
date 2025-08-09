# WSSTE
Documentation for the new WSSTE system using Airtable, Zapier &amp; Quickbooks.

- All Interfaces are [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagS3xIbYBE6UgxwW?c1i8p=rec2vWuI2rUdq4frr)

---

# How to guides

> [!Note] All public forms require this password: `WSSTE123!`

## For Brand new families (these forms only need to be filled out once by brand new students).
1. New Parent Registration [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagU6dBycz0eKy5Wn/form)
    - New families must FIRST register parents.
2. New Student Registration [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagLsfmfEQsw0WJvX/form)
    - Next, the student can then be registered.
    - Parents must register first because inside the student registration form, you must link the parent to the student.

## Managing Tuition Terms

### Yearly
1. Create a new Yearly Cycle in the Fall [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagxKkpRdEMR8jBIH/form)
    - This serves as the base for every student that registers for the year.
    - All you need to do is tell us "when the year starts".
    - You will reference this Yearly Cycle in future forms to keep the data organized.
2. Student Yearly Registration [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagLsfmfEQsw0WJvX/edit)
    - All students who are enrolled in the year must fill out this form.
    - The purpose of this form is to collect information about who your teacher is, when your lesson is, etc.
    - This does not need to be filled out by the students, it should either be filled out by Emily or the teacher whose student they are enrolling.

### For Tuition Term (Fall, Winter, Spring, Summer)
1. Create a new Tuition Term [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagfHstbw14bcn0tf/form)
    - You will create a new Tuition Term for each season in the year (Fall, Winter, Spring, Summer).
    - Tuition Terms will serve as the base for the invoices that you generate for said term, for each student (who has been registered in the Yearly Cycle).
2. Fill out holiday schedule for created Tuition Term [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagxx72tD84KRN9Yx/form)
    - This is to designate Spring Break, Winter Break, etc... anything where if the student is supposed to have a lesson on these days, those lessons are simply rescheduled for later in the Tuition Term.
3. Fill out Teacher Preemptive Days Off [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagBzJkamyCiyaYCB/form)
    - These are days where the teacher has specified that they are taking off prior to the start of the term.
    - Lessons missed as a result of these days will NOT be made up later in the term.
4. Check the "Yearly Enrolled Students" table
    - Make sure that the "Is Valid For Tuition" column is set to "Yes ✅" for all students.
    - Fix any students who are set to "No ❌"
5. Check for students who only have lessons every other week (Anour Benali & Ashley Levack)
    - Step 1: Go to the "Lesson Schedule" table.
    - Step 2: Find the student in question.
    - Step 3: Delete the rows where the student does not actually have a lesson.
    - Step 4: Find the new Sum of the Cost (NOT the Sum of the Tuition Rate) for that student & paste it into the "Tuition" column of the invoice for that student.
6. Check the "Teacher Tuition Term Days Off" table
    - Make sure that everything in the "Is Valid" column is set to "✅ Valid"
7. Scenario: Sherri DeRoche preemptively told us that she won't be available on [insert date] but Tiger Mom says she wants that anyway.
    - Step 1: Go to "Tuition Term Lesson Schedule" table.
    - Step 2: Find the student in question.
    - Step 3: Add a new row for the date of the lesson that will happen anyway.
    - Step 4: Copy the "Cost" column from the "Lesson Schedule" table into the "Tuition" column of the invoice record for that student.
8. Generate invoices for this tuition term [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagsr7bDhKDS3hs2Y?zFlyI=recN7jeWj66D8kEvE)
    - Only do this once everyone has been registered for the year, because that's how we build their invoice total, and schedule their lessons, and we need their lesson information in order to calculate all of that.

### Ensemble Terms
1. Create a new Ensemble Term [Here](https://airtable.com/appQuyMgZDPmykQ6B/pag3DGiI6i24hGMOu/form)

## Other Forms

- Log a staff event [Here](https://airtable.com/appQuyMgZDPmykQ6B/pag59Vmt5M8x40hDa/form)
- Teacher taking a vacation [Here](https://airtable.com/appQuyMgZDPmykQ6B/pagBzJkamyCiyaYCB/form)
- Issue miscellaneous student credits/refunds [Here](https://airtable.com/appQuyMgZDPmykQ6B/pag9rp2CFfOR3XLMo/form)

### Lesson Question Set

1. Did the teacher accumulate paid leave?
    1. Yes
        1. The lesson happened
        2. The student missed the lesson (we do not penalize the teacher)
    2. No
        1. The teacher went on vacation
2. Are we paying the teacher for this lesson?
    1. Yes
        1. The lesson happened
        2. The student missed (we do not penalize the teacher)
        3. School event conflicted with lesson
        4. Teacher used paid leave
    2. No
        1. Teacher took off (did not have enough, or did not use paid leave)
3. Did the teacher use paid leave?
    1. Yes
        1. They took the lesson off, and they used paid leave
    2. No
        1. Every other scenario (you just aren’t using paid leave)
4. Are we issuing a credit for this lesson?
    1. Yes
        1. The teacher missed the lesson
        2. School event conflicted with a lesson
    2. No
        1. Every other scenario (student paid full price for the lesson)