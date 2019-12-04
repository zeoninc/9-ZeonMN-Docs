<div class="column column-half home-getting-started">

      <h2 class="section-heading">Getting Started</h2>

      <ol class="install-steps">
        <li>
          <p>
            <a class="js-os-data" data-os-attr="href" data-ga-params="download,link" href="https://github.com/git-lfs/git-lfs/releases/download/v2.9.1/git-lfs-darwin-amd64-v2.9.1.tar.gz" data-os-mac="https://github.com/git-lfs/git-lfs/releases/download/v2.9.1/git-lfs-darwin-amd64-v2.9.1.tar.gz" data-os-windows="https://github.com/git-lfs/git-lfs/releases/download/v2.9.1/git-lfs-windows-v2.9.1.exe" data-os-linux="https://github.com/git-lfs/git-lfs/releases/download/v2.9.1/git-lfs-linux-amd64-v2.9.1.tar.gz">Download</a>
            and install the Git command line extension. Once downloaded and installed, set up Git LFS and its respective hooks by running:
          </p>
          <pre>git lfs install</pre>
          <p>You'll need to run this in your repository directory, once per repository.</p>
        </li>
        <li>
          <p>Select the file types you'd like Git LFS to manage (or directly edit your .gitattributes). You can configure additional file extensions at anytime.</p>
<pre>git lfs track "*.psd"</pre>
          <p>Make sure .gitattributes is tracked</p>
<pre>git add .gitattributes</pre>
        </li>
        <li>
          <p>There is no step three. Just commit and push to GitHub as you normally would.</p>
<pre>git add file.psd
git commit -m "Add design file"
git push origin master</pre>
        </li>
      </ol>

      <h2 class="section-heading">Git LFS is an open source project</h2>

      <p>To file an issue or contribute to the project, head over <a href="https://github.com/git-lfs/git-lfs?utm_source=gitlfs_site&amp;utm_medium=repo_link&amp;utm_campaign=gitlfs">to the repository</a>
        or read our <a href="https://github.com/git-lfs/git-lfs/blob/master/CONTRIBUTING.md?utm_source=gitlfs_site&amp;utm_medium=contributing_link&amp;utm_campaign=gitlfs">guide to contributing</a>.</p>
      <p>If you're interested in integrating Git LFS into another tool or product, you might want to read the
        <a href="https://github.com/git-lfs/git-lfs/blob/master/docs/api/README.md?utm_source=gitlfs_site&amp;utm_medium=api_spec_link&amp;utm_campaign=gitlfs">API specification</a>
        or check out our <a href="https://github.com/git-lfs/lfs-test-server?utm_source=gitlfs_site&amp;utm_medium=reference_servedr&amp;utm_campaign=gitlfs">reference server implementation</a>.</p>

    </div>
