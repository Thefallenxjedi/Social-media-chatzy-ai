# Chatzy AI Complete Work Tracker

This document contains every single task, bug fix, feature, and operational item from the engineering backlog. 

| Task / Feature | Status | Additional Notes / Assignee |
| :--- | :--- | :--- |
| WA message breaking | - | Rohit |
| Add logs on the front end for flow based ai agents and journeys so that users can check the error and debug themselves. | Completed | Ayush |
| Moderation Layer | Completed (Jul 8) | Rohit |
| Bug: WA Message Ids properly associate with the message | Completed (Jul 8) | Ayush |
| Blacklist - Rule based | Completed (Jul 8) | Ayush |
| Create agent => there are 5 place where one can create an agent. streamline then. | Completed | Ayush, Sourabh |
| "WhatsApp message stats" graph, where we track sent delivered, read and failed should only correspond to whatsapp-template conversations | Completed | Ayush, Rohit |
| Hotjar insights - product improvements- Quick Start Button, Midway Journey Drop-off-Hotjar changes, Credits Notification- Toast- Hotjar changes, Retrain Reminder- more prominent- Hotjar changes | Completed | Ayush, Sourabh |
| option to add a point in Chatflow | Completed | |
| user, assistant messages timestamped | Completed | |
| Bug in Journey; Blacklist remove people from campaigns, journeys; webhook bug | Completed | |
| Add flow bot templates | Completed | Ayush |
| Pricing - Add option to Upgrade Teir, Remove custom_pricing logic | Completed | Ayush |
| API documentation - Conversation, Get Inference | Completed | Rohit |
| Authetication in Iframe | Completed | Ayush |
| Interactive Msgs WA - Get Location Interactive Message | Completed | Ayush |
| Click-to-WhatsApp ads, feedback loop | Running | Ayush |
| Show if the user closes the chat window midway, when a response is being generated. Then show them the generated message in the next session. | Completed | Ayush |
| Meta New Features Explore - Business number use on Cloud, MM Lite | - | Rohit |
| Video - How to create conversational AI Agent, Flow Based AI Agent | - | Rohit |
| Moderation Layer - Improvements | Completed | Ayush |
| Journey Templates | Completed | Ayush |
| pritesh bug | Completed | |
| Campaign Pacing - If sending to contacts greater than allowed then auto pace for next day. | Paused | Ayush |
| WA Number Quality Tracking - Email, Quality in Red then pause campaign | Completed | Rohit |
| User's LLM API Key check | - | |
| Razorpay | - | |
| File input gemini, Google STT | Completed | Rohit |
| Ayush - bug fix (new journey templates add, gen ai key in api key input, Make conversation inbox searchable by iframe_user_id, all models failed server crash, freeze the person for 24 hours in abuse) | Completed | Ayush |
| Landing page for hotel use case | Completed | Ayush |
| Auto debit and recharge whatsapp credits, ai credits | Completed | |
| Typing Indicator | Completed | |
| Contact conversation (new contact conversation, auto scroll bug) | Completed | |
| CRITICAL: db lock bug in oolka account PROD | Completed | Rohit |
| Studio: Change the color of the connector line (between 2 nodes) when selected | Completed | |
| Utm source tracking | Completed | Sourabh |
| count tokens for documents (while counting tokens in each conversation message - for gemini consider the file tokens as well) | Completed | Ayush |
| journey and flow bot execute code, add code validation feature in UI | Completed | Rohit |
| get_inference - remove credits over ??, add additional logs | Completed | |
| UX fixes for Templates (Back button routing, clicking template cards, Journey builder template preview) | Completed | Ayush |
| Shubham plan upgrade problem | Completed | |
| db lock/load too much - whatsapp webhook handler fails | Completed | |
| execute code within the journey/flow - not all functions are loaded | - | |
| iframe text to voice - AIS Glass | Completed | |
| insta, messenger fix | Completed | |
| Oolka docs | Completed | |
| Oolka - BE latency | Completed | |
| Documentation - Journey elaborate actions esp. execute code, Flow each cards elaborate usage with examples | Completed | Avinash |
| ASG for EC2 for peak system loads/heavy traffic | - | Ayush |
| Continue flow in case of errros in execute code, more better observability for the client | - | |
| AWS Storage Optimization | - | |
| Error Solving | Completed | Ayush |
| Track latency breakdown | Completed | |
| PostHog User Error Event Tracking | Completed | |
| Inject Nudge Assistant Message (P1) | Completed | Ayush |
| Pills/ Chat Suggestion (P2) | Completed | Rohit |
| Remove call_again logic | Completed | |
| Multi-Agent (P3) | Completed | Rohit |
| AIS Changes Testing + Service Center Executive Portal | Completed | Rohit |
| Evals Framework | - | Rohit |
| Conversations dashboard optimize, iframe scrolling optimizations, DB sessions > 10 (alert) | Completed | |
| Enable support for "message reaction", "sticker", "gifs" | - | |
| gpt-4o-mini credits change | Completed | |
| Usage - Track somewhere in transaction level table and update using a cron job or async update | Completed | |
| admin panel webhook | Completed | |
| Version Control for Journey, Flow-based and Conversational | - | |
| Flow bot language translation.. | Completed | |
| Top level FE chat interface, flow, conversational bot, journeys | - | |
| BSNL Mela Tasks | Completed | Ayush |
| Dashboard Correct | Completed | |
| WA Calling | Completed | Ayush |
| Campaign API Pritesh | - | |
| UTM parameter for user signing up on our platform | Completed | |
| Paywall on Whatsapp | - | |
| Voice Agent enhancements (Latency Tracking, Voice campaigns, Billing config per min cost) | Completed | Ayush |
| Dialer - we give number and we give dialer platform for human agents | - | |
| whatsapp credits usage tracking | Completed | Ayush |
| Reply to Story – Getting “Unsupported message type” error | Completed | |
| Journey send message - do not send if conversation live/close existing conversation/make the message as part of conversation | Completed | Ayush |
| Exotel Integration - Explore | Completed | |
| Frozen number in dashbaord and after that add setting on the FE | Completed | |
| Execute code logs in flow bots?? | Completed | |
| token counting in claude | - | |
| jwt_token, bearer token elif will fail | Completed | |
| multi agent conversations are being left in is_streaming and processing | - | |
| wa message ids also give in get_contact_conversation_messages | - | |
| SEO improvement web vitals, page speed | Discuss | Ayush |
| Convert Leads to contact -> journey trigger | Completed | |
| Word/Phrase trigger for Comments, Free trigger for Comments, Chatzy AI Instagram account with Demo | Yet to Start | |
| Check when multiple concurrent calls are placed, why is Twilio connected, but calls are not assigned to the livekit room | - | |
| Add filters in conversation dashboard | Completed | |
| WA Call to Twilio/Exotel handover | - | |
| Migrate to openai responses API | - | |
| Remove revise answer | Completed | |
| Add 5k plan in chatzy pricing | Completed | |
| Conversation dashboard add filter (replied last 24hrs, 7 days, ads filter) | Completed | |
| In case of manual message send, if whatsapp-template sent then insert conversation with proper type | Completed | |
| Carselona - AI Agent Retry failure (Credits over logic and queuing) | Yet to Start | |
| Carselona - multiple number same account | Completed | |
| Forced delay diff in conv vs flow bot, Reduce Latencies in DB actions, Redis task picking up freq 0.2s | Completed | |
| Whatsapp account do not disconnect immediately, wait until AI sensy renewal date comes | Completed | |
| 918310187844 - Customer sends audio and triggers the journey but the audio is not displayed | Completed | |
| Transition to MM Lite API | Completed | |
| When sending message to phone number with live conversation assistant message disappears and comes after reloading.. | - | |
| Upsert when trying to add duplicate contacts.. | Completed | |
| ilovepdf api token rotation logic, policy size increasing due to watermarking | Completed | |
| whatsapp image reading gemini oolka | Completed | |
| 10k contact import direcly, error.. | Completed | |
| twilio handover to human agent | - | |
| wa message ids null insert ho rahi iss case me... (show failed reason) | Completed | |
| prevent infinite loops in flow bots | - | |
| Manage subscription button is not showing on payment page | Completed | |
| Send WA message using API...implement queue | Completed | |
| Voice: call recording, which agent picked up, show active call, initial connection delay, multi websocket connection errors | Completed | |
| Human Temporarily take over conversation... | - | |
| Delete contact API timeout | Completed | |
| get contact conversation messages bug flow bot last conversation | Completed | |
| Connecting line highlighter for Squads | Completed | |
| Aashi bug - multiple WA message for the same number being processed by webhook parallely | Completed | |
| add rejection reason in whatsapp message templates | Completed | |
| Voice Product Features: Reduce default call termination time, Do not expose telephony in free plan, Rate limits, Fix log rotation, Add credit balance check, Cleanup orphaned logs, Disable shady email | Completed | |
| initiate WhatsApp call action } outbound calls - journeys | Completed | |
| Voice Agent: Create Voice Agent (STT/TTS), Test Voice Agent, Users can connect Plivo/Twilio | Completed | |
| Execute code logs in flow bots and journeys | Completed | |
| Ai credit usage, WA credit usage report as a platform feature | - | |
| AI Sensy WA template message pricing updates - increase prices and communicate | Completed | |
| Send marketing template messages using MM Lite endpoint, Onboarding accounts on MMlite | Completed | |
| oolka soham...wa message gpt should read.. | Completed | |
| clevertap integration | Completed | |
| WA Calling Enhancements: Outbound call FE notifications, Assign incoming calls to different team agents, Iframe widget for calls | - | |
| Remove follow up suggestions from flow base bot, Remove disable reset button | Completed | |
| Flowbot - Notifications - Make relevant to flowbots | - | |
| create_wa_settings (bug fix) | Completed | |
| Reports with conversational intelligence per chatbot (Top 10 unresolved queries, Sentiment) | - | |
| Redash Quick, AWS Another Data Layer for reporting | Running | Ayush |
| Stripe TDS provision - BSNL | Completed | Rohit |
| onboarding FE design changes.. | Completed | Ayush |
| Instagram Unsupported Message Types | Completed | Ayush |
| Whatsapp messages "failed" - show reason on the FE | Completed | Ayush |
| Show Tier Limits and usage, Billing UI changes | Completed | Ayush |
| Enforce Tier Limits (need to think how custom limits can be enforced for clients like pritesh) | - | |
| Conversation - filter by channel | Completed | |
| Campaign Bulk Send | Completed | |
| show failed reason for "not sent" messages | Completed | Ayush |
| emails/wa messages should trigger only once for upgrade reminders until next recharge and WA credit notifications over WhatsApp | Completed | Ayush |
| Migrate from pinpoint to posthog + Send AI credits and... | Completed | Ayush |
| Helper Chatbot based on youtube videos and docs page | Running | Rachit |
| docs include a flow chart | Completed | Avinash |
| Iframe UI updates | Completed | |
| adhocs - install older db extensions in new db, ais oval icon | Completed | |
| send tier message limit exhaustion email () | Completed | |
| Nova-3 (Monolingual) is now available, Nova-2 can be sustituted, voice AI pricing update in the platform | Completed | |
| flow-based: Translate the language options into the respective scripts | Completed | |
| Saarthi API, Parivahan API fetch frequency | Completed | |
| Improve AIS OCR pipiline | Completed | |
| Assign feature of messages on chatzy | Completed | |
| new journey action - Integrate Google Sheets | Completed | |
| system prompt versioning and mapping for each message | Completed | |
| PDF sharing option in data - Conv. AI agent | Completed | |
| too many concurrent requests in inbound webhook -> system lags -> race conditions | - | |
| CHECK COMMERCIAL VEHICLE ROAD TAX IS LIFE TIME AND VALIDITY AND CUSTOMER NAME NOT ON ON TAX RECEIPT | Completed | |
| dialer | - | |
| New Sarvam model tts, 4 new languages with DG, add Sarvam transcriber - multiple Indian languages switching | Completed | |
| Deleting contacts and deleting journey runs is not working in the platform. | Completed | |
| Develop co-existence/Mobile app/Webapp (same UI - PWA) | Completed | Ayush |
| Shopify feature: Journey Runs getting trigerred again and again – abandoned checkout, Show product images in the abandoned cart message | Completed | |
| Redirect the user directly to the particular node by skipping the previous steps in the flow | - | |
| Voicebot latency monitor and testing, New Sarvam models, Deepgram flux model, Live kit inference check, Instagram comments, CAPI error tester account | Completed | |
| Detailed report for Campaign data | Completed | |
| IG messages syncing (msgs sent using mobile phone directly) | - | |
| Message Template Preview on selection | Completed | |
| Instagram Comments | Completed | |
| Import Contact CX enhancements | Completed | |
| Name of the chatbot that is assigned | Completed | |
| campign template preview should come first | Completed | |
| add option to config conversation id in case of Assign to Human action | Completed | |
| WA settigs webhook timeout issue | Completed | |
| Copy/ duplicate action cards in Journey | Completed | |
| what message template was sent in the campaign and some campaign stats like total recipients | - | |
| Anthropic Alert | - | |
| pricing enhancements + voice ai + mltiple whatsapp number, insta automation, additoinal services, make corra club pay | - | |
| autosaving chatbot settings while working on them, not publishing, same for journey | Completed | |
| Pritesh's problems - retrigger when chat stopped due to lack of AI credits | - | |
| Add a journey action: Send Email (to be used to send lead notifications) | Completed | |
| Notif when k or notification laga skta hi kya jb hamari api use hona bnd ho jaye chatzy use hona chalu ho tb ka | - | |
