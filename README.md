# Web Accessibility Checklist
This checklist is a general guideline, not a final confirmation that a given page or site is accessible. It only includes success criteria up to level AA of the WCAG recommendations, and is not 100% comprehensive. I’ve tried to break requirements into individual items to check.

Drawn from [DubBots Beginners Guide to Accessibility testing and WCAG.xlsx](https://docs.google.com/spreadsheets/d/1THhb_vt_bUoorw8YqxaqjjN7EJiI4eN-/edit#gid=1816335579)

## Perceivable
[] All images have alt text.
[] Alt text is useful (not the same as filename, marks decorative elements, provides information rather than a visual description)
[] All “images of text” (e.g., a certificate or award graphic) have alt text which makes the full text of the image available. Ideally, no images (other than logos) contain text which is important to understanding the image.
[] All audio has a transcript.
[] All videos have a transcript.
[] Videos have captions/subtitles with all spoken content available in text, as well as descriptions of sounds (music, laughter, applause, etc.)
[] Videos make the visual content available through text, if it is important (e.e.g, video tutorials should have descriptions of the blackboard an instructor writes on)
[] All audio and video can be controlled by the user, including start/stop/volume.
[] Headers accurately describe the reading sequence of a document.
[] Interactions (e.g., links, forms, maps) have multiple cues for users (e.g, form errors are not color-only).
[] All pages work in portrait and landscape mode. Prioritize navigation and interaction (e.g., slideshows).
[] All inputs have labels.
[] All text has a color contrast with its background of at least a contrast ratio of at least 4.5:1. This includes icons and controls, such as buttons.
[] All content is available to a user zooming their browser to 200%.tx

## Operable
[] Users can navigate site navigation only using a keyboard.
[] If a keyboard user can focus on/access an element, they should be able to move away from it.
[] A user should be able to control the timing on any element which may “time out”. For example: users should be able to pause slideshows or adjust the speed of a video.
[] Any content which moves, blinks, or scrolls, should be controllable by the user.
[] Videos and images which flash should flash no more than 3x per second.
[] Users can skip repetitive content (e.g., navigation or callouts that appear on multiple pages).
[] Users can get to the main content of the page without having to traverse all the items in a menu.
[] All pages should contain a unique title which describes the page content.
[] Focus order follows the logical order of the content a user expects to be able to access.
[] Tables can be focused by row, tabbing to successive cells in a rows, or focused by column, reading down the values of each column,
[] Slideshows/carousels can be controlled by the left/right arrow keys.
[] Tabbing should take the user to the next link in a list, and shift + tab brings them to the previous link.
[] All links use descriptive text. Text should ensure the user understands what they are clicking on and the link destination is expected.
[] A site can be navigated in multiple ways: e.g., a site menu and a site map and a search bar.
[] Headers are descriptive of the content following.
[] Form labels are descriptive of the expected input.
[] A user navigating with keyboard can see where they are in a page. When tabbing or moving between linked or other focused content, the currently-focused element should be distinct.
[] Buttons and links are activated on release rather than click down event.
[] The name of each input field must begin with the text of a visually supplied label.

## Understandable
[] The page’s language is set.
[] If a page has multilingual content, the sections have appropriate language tags.
[] Selecting or focusing content does not change the page context (e.g., form inputs which progressively expose other fields), unless the user is aware that this will happen before the interaction.
[] Navigation is consistent throughout the site.
[] Components are consistent throughout the site.
[] Form input error messages are explained in text and provide an explanation of the anticipated correct input (e.g., minimum/maximum character length, required character types).
[] All inputs are labeled in text.
[] The user can update a form when an error occurs without having to start the process from scratch.
[] The user can review the form data before completing submission.

## Robust
[] All HTML is valid.
[] All names of controls describe the interactive functionality (e.g., stop, play, pause, open, close) of the control.
[] When content updates, the user is notified (e.g., a search status or errors in a form).
