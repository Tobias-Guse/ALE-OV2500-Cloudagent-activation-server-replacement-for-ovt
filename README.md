# ALE-OV2500-Cloudagent-activation-server-replacement-for-ovt


Goal:
Cloud agent activation server replacement for migration to OmniVista Terratest with AOS 8.10R4

The sed command is a tool used to edit text in files. The -i option modifies the file directly without creating output or a backup. The s stands for substitute (replace). The pattern ^Activation Server URL: searches for a line that starts with this text, while .* represents everything that follows in that line. The entire matched line is then replaced with Activation Server URL: activation.myovterra.com. The change is applied to the file working/cloudagent.cfg.
