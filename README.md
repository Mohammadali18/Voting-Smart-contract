# Voting-Smart-contract
Voter and Candidate Registration: Only eligible voters (18+ years) and unique candidates can register.
Voting Process: Voters can cast votes during the active voting period, and each voter can vote only once.
Election Commission Management: The Election Commission sets the voting period, stops voting in emergencies, and announces results.
Real-time Voting Status: Check if voting is not started, in progress, or ended.
Contract Details

## Features

**Voter and Candidate Registration**: Only eligible voters (18+ years) and unique candidates 
  can register.
**Voting Process**: Voters can cast votes during the active voting period, and each voter can 
  vote  only once.
**Election Commission Management**: The Election Commission sets the voting period, stops 
  voting in emergencies, and announces results.
**Real-time Voting Status**: Check if voting is not started, in progress, or ended.
 Contract Details

## Contract Details

 **Contract Name**: Vote
 **Compiler Version**: Solidity ^0.8.26
 **License**: MIT

## Functions

**RegisterVoter**: Registers a new voter with details.
**RgisterCandidate**: Registers a candidate for the election.
**SetVotingPeriod**: Sets the voting start and end times.
**CastVote**: Allows a voter to vote for a candidate by ID.
**GetVotingStatus**: Returns the current voting status.
**AnnounceVotingResult**: Determines the winner based on votes.
**EmergencyStopVoting**: Stops voting in case of emergency.

## Usage

1.Deploy the Contract: Only the deployer becomes the Election Commission.
2.Register Candidates and Voters: Call registerCandidate and registerVoter with required 
  parameters.
3.Set Voting Period: Election Commission sets the voting period with setVotingPeriod.
4.Cast Votes: Registered voters can vote during the active period with castVote.
5.Get Results: After voting ends, 
 announceVotingResult reveals the winner.



