&nbsp; &nbsp; &nbsp;
<link rel="icon" href="https://i.postimg.cc/zDxqGzWD/NS-Icon.png" type="image/png" sizes="48x48">
<meta charset="UTF-8">&nbsp;
<title>ASTRO CRICKET</title>&nbsp;
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">&nbsp;
<meta name="referrer" content="no-referrer">
<meta name="viewport" content="width=device-width, initial-scale=1.0">&nbsp;
<script src="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka.js"></script>
<script src="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka-player.ui.js"></script>
<script disable-devtool-auto='true' src='https://cdn.jsdelivr.net/npm/disable-devtool' clear-log='true' disable-select='true' disable-copy='true' disable-cut='true' disable-paste='true'></script>
<script src="/sec/prodevs.js"> </script>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka.css">&nbsp;
<style>
  #tglogo {
    position: absolute;
    left: 10px;
    top: 10px;
    height: 35px;
    width: 100px;
  }

  .uc {
    pointer-events: none;
  }
</style>
<div data-shaka-player-container="" style="max-width: 100em; cursor: none;" data-shaka-player-cast-receiver-id="8D8C71A7" shaka-controls="true" class="shaka-video-container">
  <video autoplay="true" data-shaka-player="" id="video" poster="https://i.ibb.co/6vQmqJY/Astro-Cricket.jpg" style="width: 100%; height: 100%;" class="shaka-video" src=" "></video>
  <script>
    async function init() {
      let _0x266839 = document.getElementById('video'),
        _0x3d6bb6 = _0x266839.ui,
        _0x6a17ef = _0x3d6bb6.getControls(),
        _0x2ccaff = _0x6a17ef.getPlayer()
      _0x2ccaff.configure({
        drm: {
          clearKeys: {
            '03c2e0af2f8159f9f0ce9b5dbc865f10': 'cd84ed136b0cc71f8ab8cd4d4f6a2e4c',
          },
        },
      })
      _0x3d6bb6.configure({
        controlPanelElements: [
          'play_pause',
          'mute',
          'spacer',
          'time_and_duration',
          'quality',
          'fullscreen',
          'overflow_menu',
        ],
      })
      window.player = _0x2ccaff
      window.ui = _0x3d6bb6
      _0x2ccaff.addEventListener('error', onPlayerErrorEvent)
      _0x6a17ef.addEventListener('error', onUIErrorEvent)
      try {
        await _0x2ccaff.load(
          'https://linearjitp02-playback.astro.com.my/dash-wv/linear/2504/default_primary.mpd'
        )
        console.log('The video has now been loaded!')
      } catch (_0xc64dbb) {
        onPlayerError(_0xc64dbb)
      }
    }
    function onPlayerErrorEvent(_0x1760fd) {
      onPlayerError(event.detail)
    }
    function onPlayerError(_0x3c25fa) {
      console.error('Error code', _0x3c25fa.code, 'object', _0x3c25fa)
    }
    function onUIErrorEvent(_0x4c7277) {
      onPlayerError(event.detail)
    }
    function initFailed(_0x103924) {
      console.error('Unable to load the UI library!')
    }
    document.addEventListener('shaka-ui-loaded', init)
    document.addEventListener('shaka-ui-load-failed', initFailed)
    true ==
      confirm('Join us on telegram Group to get All Updates @bjtech_2426') &&
      window.open('https://t.me/bjtech_2426', '_blank')

  </script>
  </body>

  </html>
