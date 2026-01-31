# os_timelines
Timelines of major Operating Systems

An interactive, visual history of the three major operating system families: **Windows**, **Linux**, and **macOS**. This project utilizes [TimelineJS3](https://timeline.knightlab.com/) to create a rich, media-heavy exploration of computing history. Details on usage of TimelineJS are available at the project's page.

You can view the main landing page and navigate to the individual timelines here:
**https://presack.github.io/os_timelines/**

![Project Screenshot](images/screenshot.png)

## Project Structure
* `index.html`: The main landing page with responsive "OS Cards."
* `windows_timeline.html`, `apple_timeline.html`, `linux_timeline.html`: The individual timeline viewers.
* `images/`: Local repository for all media assets (ensures long-term link stability).
* `scripts/`: Python utilities used to sync and download external media to the local images folder.

## 🛠️ Features
- **Categorized Milestones:** Events are grouped (e.g., "Corporate Milestones," "Kernel & Community") to allow for easy filtering within the timeline.
- **Narrative-Driven Content:** Descriptions focus on the "why" behind the tech, highlighting pivots like the NeXT merger or the Linux supercomputer dominance.
- **Fully Responsive:** The CSS is optimized for desktop, tablet, and mobile viewing.
- **Local Asset Management:** Includes Python scripts to programmatically download images from JSON URLs to prevent "link rot."
The script will download all remote assets into the `/images` directory for local hosting.
