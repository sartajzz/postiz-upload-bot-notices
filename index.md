---
layout: default
title: Privacy Policy — Postiz Upload bot
---

# Privacy Policy — Postiz Upload bot

**Last updated: 30 October 2026**  
**Service:** Postiz Upload bot  
**Operator/contact:** The operator of Postiz Upload bot, reachable at [sartajprince1@gmail.com](mailto:sartajprince1@gmail.com).

## What this service does

Postiz Upload bot is a private, allowlisted WhatsApp upload utility operated on the operator’s computer. It receives supported MP4 documents or videos from approved senders and transfers them to the operator’s self-hosted Postiz media library. It is not an official WhatsApp, Meta, Instagram, or Postiz service.

The bot sends automated upload-status replies only to approved senders. It does not create social-post drafts, schedule posts, or publish videos to Instagram. It stores notification timestamps, delivery outcomes, and hash-based sender references locally. Any later social-media publication through Postiz is a separate action controlled by the operator. Send only material you are entitled to share, with appropriate permission from people shown in it.

## Information processed

The service receives message updates from Meta/WhatsApp. These can include the sending phone number, message and media identifiers, document filename, media type, caption, and routing or timestamp information. It uses this information to check the destination, approve the sender, identify a supported file, and prevent duplicate processing.

For accepted uploads, it processes the video itself and records the message/media identifiers, a shortened hash-based sender reference, filename, caption, processing timestamps, job status, and upload results. A hashed sender reference is not treated as fully anonymous. The approved sending numbers are kept in private local configuration.

Other messages and updates may be examined transiently to validate and classify delivery, but unsupported messages and messages from unapproved senders are not added to the upload queue. The bot’s diagnostic counters record event categories, counts, and timestamps rather than raw message bodies. Infrastructure providers may separately process connection information, such as IP addresses, request metadata, and service errors.

## Why the information is used

The information is used to operate the requested upload workflow, check file integrity, enforce the sender allowlist, avoid duplicate uploads, and diagnose processing failures. The bot has no implemented advertising, data-selling, or paid-AI processing feature. Captions in local upload records do not automatically become social-post captions.

## Where information goes and who can access it

Meta/WhatsApp handles messages and media under its own terms and privacy practices. The bot obtains accepted media through Meta’s authenticated API and transfers it to Postiz running on the operator’s computer. Cloudflare Tunnel forwards traffic to the webhook and the separately exposed application endpoints; Cloudflare may process traffic and technical data as an infrastructure provider.

When you visit the public privacy or deletion notices on GitHub Pages, GitHub logs visitors’ IP addresses for security purposes. Only the public notice documents are hosted through GitHub Pages; the bot, videos, credentials, and private upload database remain on the operator’s computer.

The operator and people granted access to the operator’s computer or Postiz can access stored uploads and related records. Uploaded Postiz media can also be reachable through public media URLs used by the self-hosted publishing workflow. Anyone who obtains an accessible public media URL may be able to view or download that file. Do not treat this workflow as confidential storage for sensitive material.

The bot does not itself publish videos or transmit them to unrelated advertising or AI services. If the operator separately publishes a file to Instagram or another platform, that platform’s visibility rules and privacy practices apply to the published copy.

## Storage, retention, and security

The bot stores its configuration and accepted-job records locally. It verifies Meta webhook signatures, restricts the expected account and phone, checks the approved sender, and validates accepted files before uploading. These measures reduce risk but cannot guarantee complete security. Delivery counters are not a substitute for securing the operator’s computer and accounts.

After a successful upload, the bot attempts to remove its temporary local video copy. A cleanup failure, failed job, or uncertain upload may leave a local copy for operator review. The Postiz media copy and local job records, including captions and identifiers, remain until the operator deletes them. **No automatic expiry or fixed retention period is currently configured.** Any operator-created backups must also be considered when handling a deletion request.

## Access, correction, and deletion requests

Contact [sartajprince1@gmail.com](mailto:sartajprince1@gmail.com) to ask about your data, correct relevant information, request deletion, or stop future access to the upload service. Use the subject **Postiz Upload bot — data request** and identify the relevant sending number and approximate upload date or filename. Do not send account passwords, API tokens, verification codes, or identity documents.

The operator handles requests manually and may ask for proportionate information to confirm that the request concerns your own data. After verification, the operator will promptly review and act on the request, including relevant bot records, retained local copies, and Postiz media. Any limitation, applicable legal retention requirement, or copy outside the operator’s control will be explained. The service does not have an automatic deletion callback or a guaranteed software-driven deletion deadline.

Deleting a WhatsApp chat message does not by itself delete a file already copied into Postiz. If a file was separately published to a social platform, identify that publication in your request so the operator can review that copy too. Copies retained by Meta/WhatsApp or by other people are subject to those parties’ control and policies.

## Changes and contact

The operator will update this notice when the service’s practices change and maintain a publicly accessible copy while the app is published. Questions and privacy requests can be sent to [sartajprince1@gmail.com](mailto:sartajprince1@gmail.com).

[Data deletion instructions](./data-deletion.html)
