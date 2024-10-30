# Voting-Smart-contract

This Ethereum smart contract allows a decentralized voting process where eligible voters can register, vote for candidates, and track voting progress. The Election Commission (contract owner) can manage the voting period and finalize results.

#Features

.Voter and Candidate Registration: Only eligible voters (18+ years) and unique candidates can register.
Voting Process: Voters can cast votes during the active voting period, and each voter can vote only once.
Election Commission Management: The Election Commission sets the voting period, stops voting in emergencies, and announces results.
Real-time Voting Status: Check if voting is not started, in progress, or ended.
Contract Details
Contract Name: Vote
Compiler Version: Solidity ^0.8.26
License: MIT
Functions
registerVoter: Registers a new voter with details.
registerCandidate: Registers a candidate for the election.
setVotingPeriod: Sets the voting start and end times.
castVote: Allows a voter to vote for a candidate by ID.
getVotingStatus: Returns the current voting status.
announceVotingResult: Determines the winner based on votes.
emergencyStopVoting: Stops voting in case of emergency.
Usage
Deploy the Contract: Only the deployer becomes the Election Commission.
Register Candidates and Voters: Call registerCandidate and registerVoter with required parameters.
Set Voting Period: Election Commission sets the voting period with setVotingPeriod.
Cast Votes: Registered voters can vote during the active period with castVote.
Get Results: After voting ends, announceVotingResult reveals the winner.
