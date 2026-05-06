BEGIN FUNCTION MorningSyncMeeting()
    PRINT "Team Lead: Good morning team, let's review current system status."

    PRINT "SysAdmin: ALERT! The email server is DOWN since 2:00 AM."
    PRINT "Developer A: Understood. Let me PING the infra team for support."

    PRINT "QA Tester: There’s a BUG affecting the checkout button on mobile."
    PRINT "Developer B: I saw that too. Let's reproduce it in the SANDBOX environment first."

    PRINT "Team Lead: Confirm this is not affecting PROD?"
    PRINT "QA Tester: Correct, PROD is stable. Only SANDBOX shows the issue."

    PRINT "Developer A: I’ve written a HOTFIX and pushed it to the staging branch."
    PRINT "SysAdmin: Great. We’ll apply the PATCH to the live server after approval."

    PRINT "Security Analyst: Also, I found traces of a BACKDOOR in the old admin panel."
    PRINT "Developer B: That panel is a LEGACY module. We should plan to retire it soon."

    PRINT "Team Lead: Excellent updates. Continue monitoring and PING me for urgent issues."
END FUNCTION

CALL MorningSyncMeeting()

/* 
===========================================================================
README: OPERATIONAL DEFINITIONS
===========================================================================
- PING: To test connectivity or send a quick notification to a team/person.
- DOWN: A state where a system or service is completely inaccessible.
- BUG: An unintended flaw or error causing a system malfunction.
- SANDBOX: An isolated testing environment for safe experimentation.
- PROD: The live "Production" environment used by end-users.
- HOTFIX: A critical, urgent update applied to fix a major issue quickly.
- PATCH: A specific set of code changes to resolve bugs or update features.
- BACKDOOR: A hidden entry point bypassing security; a vulnerability.
- LEGACY: Outdated software or modules slated for eventual retirement.
===========================================================================
*/

// Main Meeting Function
function MorningSyncMeeting() {
    console.log("Team Lead: Good morning team, let's review current system status.");
    
    console.log("SysAdmin: ALERT! The email server is DOWN since 2:00 AM.");
    console.log("Developer A: Understood. Let me PING the infra team for support.");

    console.log("QA Tester: There’s a BUG affecting the checkout button on mobile.");
    console.log("Developer B: I saw that too. Let's reproduce it in the SANDBOX environment first.");

    console.log("Team Lead: Confirm this is not affecting PROD?");
    console.log("QA Tester: Correct, PROD is stable. Only SANDBOX shows the issue.");

    console.log("Developer A: I’ve written a HOTFIX and pushed it to the staging branch.");
    console.log("SysAdmin: Great. We’ll apply the PATCH to the live server after approval.");

    console.log("Security Analyst: Also, I found traces of a BACKDOOR in the old admin panel.");
    console.log("Developer B: That panel is a LEGACY module. We should plan to retire it soon.");

    console.log("Team Lead: Excellent updates. Continue monitoring and PING me for urgent issues.");
}

// Execute the meeting
MorningSyncMeeting();
