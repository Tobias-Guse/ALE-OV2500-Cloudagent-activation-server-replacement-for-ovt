# ALE-OV2500-Cloudagent-activation-server-replacement-for-ovt
The scripts update the activation server, remove old certificate files, restart the cloud agent, and verify connectivity to ensure a successful migration to OmniVista Terra.

Goal:
Replace the cloudagent.cfg file on an OmniSwitch running AOS 8.10R4 for migration to OmniVista Terra.
The existing OV2500 CLI scripting module is used

Actions
Replace Activation Server URL
Remove old certificates
Restart cloud agent
Verify status

The sed command is a tool used to edit text in files. The -i option modifies the file directly without creating output or a backup. The s stands for substitute (replace). The pattern ^Activation Server URL: searches for a line that starts with this text, while .* represents everything that follows in that line. The entire matched line is then replaced with Activation Server URL: activation.myovterra.com. The change is applied to the file working/cloudagent.cfg.
