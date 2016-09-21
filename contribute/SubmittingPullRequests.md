To improve tracking of who did what, we use the "sign-off" procedure
introduced by the Linux kernel. The sign-off is a simple line at the
end of the explanation for the commit, which certifies that you wrote
it or otherwise have the right to pass it on as free software.
The rules are pretty simple: if you can certify the Developer's
Certificate of Origin 1.1 (see the [developer-certificate-of-origin
file][dcofile]), then you just add a line saying

````
  Signed-off-by: Random J Developer <random@developer.example.org>
````

using your real name (sorry, no pseudonyms or anonymous
contributions).  This line can be automatically added by git if you
run the git-commit command with the -s option.

If you like, you can put extra tags at the end:

1. "Reported-by:" is used to credit someone who found the bug that
   the patch attempts to fix.
2. "Acked-by:" says that the person who is more familiar with the area
   the patch attempts to modify liked the patch.
3. "Reviewed-by:", unlike the other tags, can only be offered by the
   reviewer and means that she is completely satisfied that the patch
   is ready for application.  It is usually offered only after a
   detailed review.
4. "Tested-by:" is used to indicate that the person applied the patch
   and found it to have the desired effect.

You can also create your own tag or use one that's in common usage
such as "Thanks-to:", "Based-on-patch-by:", or "Mentored-by:".

[dcofile]: https://github.com/nextcloud/server/blob/master/contribute/developer-certificate-of-origin
