# Contributing Guidelines 
We would love for you to contribute to Blazor School Docs and help make it even better than it is today! As a contributor, here are the guidelines we would like you to follow:
 - [Code of conduct](#coc).
 - [Terms and conditions](#tac).
 - [Commit message guidelines](#cmg).
 - [Pull request checklist](#prc).
 
 ## <a name="coc"></a>Code of conduct
 Help us keep Blazor School Docs open and inclusive. Please read and follow our [Code of Conduct](https://github.com/Blazor-School/blazor-school-docs/blob/master/CODE_OF_CONDUCT.md).
 
 ## <a name="tac"></a>Terms and conditions
 1. You hereby grant to Blazor School the ownership of your work without any condition. Blazor School is rightfully to use your contribution to do whatever with it.
 2. You are not expected to provide support for your contributions.
 3. You entitled that you are the original creator of your contributions.
 
 ## <a name="cmg"></a>Commit message guidelines
 We have very precise rules over how our Git commit messages must be formatted. This will help the community to understand your contribution.
 - Your commit messages must end with a dot (.). You need to understand that commit message is not title and not to try to write one.
 - Your commit messages must have a clear on what is updated or why do you update. For example, your commit message can be "Add a new way to do X." or "Remove some outdated parameters.".

 ## <a name="prc"></a>Pull request checklist
 To ensure consistency throughtout tutorials, keep these rules in mind as you are working:
 - Must have table of content at the top.
 - Sections:
   + Must separate sections by `<hr class="my-4">`
   + Must begin with `<h1>` tag.
 - Images:
   + Must be placed within the tutorial folder.
   + `<img>` tag must have `alt`, `width`, `height`, `src` attributes.
 - Code sample must:
   + HTML encoded.
   + Wrapped inside `pre` tag.
   + `pre` tag must have `language` attribute and it must match with the language you want to format.
   + `language` attribute must be one of the value: js, batch, csharp, razor, css, html, json.
 - Video must:
   + Video must be typed of mp4.
   + Be wrapped inside `<div class="ratio ratio-21x9"></div>`. 
   + You must use `video` tag for video. The `video` tag must have `weight`, `height`, `controls="controls"` as attributes.
   + You must have `source` tag to refer to the video. The `source` tag must have `type="video/mp4"`.
   + A good example of a video: 
   ```
   <div class="ratio ratio-21x9">
    <video controls="controls" width="300" height="150">
        <source src="\contents\blazor-wasm\dotnet5\theming-and-layout-652073\d0c5ffb2-07aa-4a7c-83bf-abc1fbcaf4fd..mp4" type="video/mp4">
    </video>
   </div>
   ```
 - Should have a PoC project.
