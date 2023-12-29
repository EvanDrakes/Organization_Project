# Organization Project

## Which coding software get paid the most?

SELECT ConvertedCompYearly, LanguageHaveWorkedWith
FROM `my-data-project-392401.Annual_Developer_Survey.survey_results`
WHERE ConvertedCompYearly IS NOT NULL
ORDER BY ConvertedCompYearly ASC

## How much does remote working matter?

SELECT RemoteWork
FROM `my-data-project-392401.Annual_Developer_Survey.survey_results`
WHERE RemoteWork IS NOT NULL
ORDER BY RemoteWork DESC

## How does coding experience affect level of pay?

SELECT YearsCode, ConvertedCompYearly
FROM `my-data-project-392401.Annual_Developer_Survey.survey_results`
WHERE ConvertedCompYearly IS NOT NULL
ORDER BY YearsCode ASC

## What is the most popular method of learning to code?

SELECT LearnCode
FROM `my-data-project-392401.Annual_Developer_Survey.survey_results`
WHERE LearnCode IS NOT NULL
ORDER BY LearnCode ASC

*after all this has been processed I would then make a dashboard or graph to show each result visually and go more in depth on how each on funcitons*
