# Plugin name

Some descriptions here

## Development

## Release

Release is simple by using the github-action. A workflow has been defined at `.github/workflows/release.yml` to describe the release flow:

- Do the cross-compile on the plugin source code
- Publish the built artifacts to NPM

Follow below steps to trigger a new release action:

1. Setup NPM token in your project settings(only once):

   ![](https://p5.music.126.net/obj/wo3DlcOGw6DClTvDisK1/14904863858/01c7/0999/8734/3e47114278e13a443f11b4f93d4f483e.png)

2. Create new release on the Releases page:

   ![](https://p5.music.126.net/obj/wo3DlcOGw6DClTvDisK1/14904788539/33d2/37ac/790a/f9b44c6714259208a2964d869b822c95.png)

3. After the "Publish release" button is clicked, the release processes defined in the `release.yml` mentioned above will run automatically

   ![](https://p5.music.126.net/obj/wo3DlcOGw6DClTvDisK1/14904909779/212c/d518/5ff9/aec6a495b34c5f59c860712a6c25ae48.png)

4. The progress of the processes run in previous step can be found on the Actions page:

   ![](https://p6.music.126.net/obj/wo3DlcOGw6DClTvDisK1/14904982812/06b3/2baa/2755/32be305e7c4ba26f74ee3fa66528e56a.png)
