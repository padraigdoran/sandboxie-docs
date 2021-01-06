# Test Email Configuration

### Test and Confirm Configuration

Sandboxie offers quick configuration for most email programs. Please see [Sandbox Settings > Applications > Email Reader](ApplicationsSettings#email) for more information.

After completing the email configuration, you may want to test it to make sure that new emails will not be lost when you delete the sandbox. To do that, follow these steps:

*   Disable Internet access in the sandbox. This is a precaution measure, to make sure that your sandboxed email program cannot retrieve new mail messages before you confirm the configuration is correct:  
    Open [Sandbox Settings > Restrictions > Internet Access](RestrictionsSettings#internet), then click _Block All Programs_, and finally click _OK_.

*   Run your email program _sandboxed_ under Sandboxie. (You can use the _Run Email Reader_ command from the [Tray Icon Menu](TrayIconMenu) of [Sandboxie Control](SandboxieControl).)

*   Compose a test draft message to yourself. Don't send it.

*   Quit your email program. If your email program suggests to send the test message, disregard the suggestion.

*   Delete the sandbox. (See [Delete Sandbox](DeleteSandbox).)

*   Run your email program normally, that is, _outside the supervision_ of Sandboxie.

*   Confirm that you can use the normal (unsandboxed) instance of the mail program to see and edit the test message you created.


If the email message that you created in a sandboxed instance of your email program is also accessible in the normal (unsandboxed) instance, even after the sandbox has been deleted, then the configuration is correct.

*   When done, re-enable Internet access in the sandbox:  
    Open [Sandbox Settings > Restrictions > Internet Access](RestrictionsSettings#internet), then click _Remove_ (to remove the restriction), and finally click _OK_.

For more information, see [Email Protection](EmailProtection) and [FAQ Email](FAQ_Email).
