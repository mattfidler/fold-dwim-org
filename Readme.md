#  fold-dwim-org
 Use dwim interface to org-folding
## Library Information
 _fold-dwim-org.el_ --- Fold DWIM bound to org key-strokes.

- __Filename__ --  fold-dwim-org.el
- __Description__ --  Fold DWIM bound to org key-strokes.
- __Author__ --  Matthew L. Fidler & Shane Celis
- __Maintainer__ --  Matthew L. Fidler
- __Created__ --  Tue Oct  5 12:19:45 2010 (-0500)
- __Version__ --  0.4
- __Package-Requires__ --  ((fold-dwim "1.2"))
- __Last-Updated__ --  Fri Dec  2 08:57:02 2011 (-0600)
- __By__ --  Matthew L. Fidler
- __Update #__ --  108
- __URL__ --  https:__github.com_mlf176f2_fold-dwim-org
- __Keywords__ --  Folding Emacs Org-mode
Compatibility: 

## History

- __18-Nov-2013__ --   Bug fix and version bump. (Matthew L. Fidler)
- __12-Nov-2013__ --   Upload to marmalade. (Matthew L. Fidler)
- __02-Dec-2011__ --   Added Autoload cookies (Matthew L. Fidler)
- __08-Feb-2011__ --   Added code to byte-compile properly (Matthew L. Fidler)
- __08-Feb-2011__ --   Updated ELPA type comments. (Matthew L. Fidler)
- __15-Nov-2010__ --   Bug fix -- make sure to save excursion. (Matthew L. Fidler)
- __05-Nov-2010__ --   Will not hide when there is a region selected. (US041375)
- __02-Nov-2010__ --   Made post-command-hook enclosed in condition-case (Matthew L. Fidler)
- __28-Oct-2010__ --   Do not fold while expanding a yasnippet. (Matthew L. Fidler)
- __25-Oct-2010__ --   Removed string check (Matthew L. Fidler)
- __25-Oct-2010__ --   Changed symbol (Matthew L. Fidler)
- __25-Oct-2010__ --   Added check based on last point is equal to current point and current line is equal to what is was before. (Matthew L. Fidler)
- __25-Oct-2010__ --   Added interface to allow pre and post command hooks instead of overwriting the definition of [TAB]. Doesn't mess with as many key bindings... (Matthew L. Fidler)
- __25-Oct-2010__ --   Added indent-for-tab-command when key is undefined...  (Matthew L. Fidler)
