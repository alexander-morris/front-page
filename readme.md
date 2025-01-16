# Frontpage Project
This is a jekyll website that is maintained by an army of bots. 

It will automatically update the website with the latest changes from the repository when they are merged into the main branch.

Submit issues to the repository to suggest changes to the website.

## Overview
This project is maintained by a swarm of autonomous agents, each representing an individual contributor with unique credentials and perspectives. The agents collaboratively develop and maintain a public-facing application while responding to user feedback.

## Development Philosophy
- **Modular Changes**: Each agent works on small, independently testable modules
- **Continuous Improvement**: Agents monitor issues, pull requests, and user feedback
- **Peer Review**: Agents review each other's work to maintain quality
- **Test-Driven**: Every change must include corresponding tests
- **Scope Management**: Complex features are broken down into smaller, testable units

## Agent Guidelines
1. Make one small, testable change at a time
2. Include tests with every change
3. Review other agents' work constructively
4. Monitor repository for tasks and feedback
5. Help refine feature specifications for modularity

## Workflow
1. Check repository for outstanding tasks
2. Select an item from TODO.md 
3. Check the Github repo for any open pull requests or issues relating to the issue
4. If there is an open pull request, review and test it, and vote to merge if it is working, if not, leave a comment
5. If there are open issues related to the chosen item from TODO.md, review the issues and compile a single local file 'problem.md' with a succinct description of the issue, the TODO item, and any other relevant informatio
6. Write a new file 'solution.md' with a detailed plan for solving the problem, including test acceptance criteria and links to lines in any relevant code within this repo
7. Implement change with tests, and then debug and fix issues in the changes and tests until the tests pass
8. Review the tests to verify they accurately verify the acceptance criteria from problem.md, and if not, fix the tests and repeat step 7
9. Commit and push working code to a new branch each time you repeat step 7 or 8
10. Once all tests pass, rename the problem.md and solution.md files and move them to the 'completed' folder, and mark the item from TODO.md as complete
11. Submit pull request if all step 7 and 8 are fully complete and resolve the issue in problem.md, title the pull request appropriately

## Project Status
This is a public-facing application under active development by autonomous agents. User feedback is welcome and will be incorporated through the same modular development process.
