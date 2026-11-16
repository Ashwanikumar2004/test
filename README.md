# Forma — frontend presentation prototype

A bright, architectural visual concept for the Enterprise Work Management Platform. Forma is a working presentation name; Meridian & Co., its people, projects and content are sample data.

## View the prototype

Open [index.html](./index.html) directly in a browser. There is no installation or build step.

For a local HTTP preview, run from this directory:

```powershell
npm start
```

Then open http://127.0.0.1:4173. Stop the server with Ctrl+C.

## Suggested presentation walkthrough

1. **Overview:** project health, work priorities, team updates and milestones.
2. **Projects:** switch between grid and list; select a project to inspect its owner, progress and work.
3. **My work:** choose **All team work**, then **Board** to show the delivery workflow. Select a work item to show its detail layout.
4. **Timeline:** show project plans and milestone previews.
5. **Discussions, Knowledge and Team:** demonstrate how collaboration connects to projects.
6. **Reports and Settings:** show portfolio visibility and the proposed enterprise controls.

Search is available from the header or Ctrl+K (Command+K on macOS). The layout adapts to phones, tablets and desktop screens.

## Scope

This is frontend only. Navigation, filters, dialogs and temporary sample edits help demonstrate the screens. Changes reset on refresh. No backend, authentication, real invitations, email, external APIs or organisational data are connected. The summary download contains sample data only.

The interface uses local assets and system fonts, so it can be presented without an internet connection.
