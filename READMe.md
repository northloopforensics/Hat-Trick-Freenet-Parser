# Hat-Trick-Freenet-Parser
Executable to parse Freenet installations using KAPE

This program was written for use on Kroll's KAPE tool.
Download the release and then copy the executable to: kape\Modules\bin

Also available in this repository are the Target profile (tkape) file and Module profile (mkape) file.
Copy these to the appropriate locations: kape\Targets\P2P\freenet.tkape & kape\Modules\Misc\hat-trick-freenet-parser.mkape

The tool parses: 
    The Location ID and Network Addresses of the Target System
    Downloaded and Uploaded File Information
    Peer IDs, Peer IP Addresses, and Peer-of-Peer Location IDs

Usage - Hat-Trick-Freenet-Parser.exe INPUT_FOLDER OUTPUT_FOLDER
Usage - Hat-Trick-Freenet-Parser.exe  C: "F:\Triage_Folder"
