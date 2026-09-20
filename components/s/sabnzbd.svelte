<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2zihunpi.css';
import '../../css/n/nuiom3xgn.css';
import '../../css/u/u07xh6bzl.css';
import '../../css/r/ra5mw5bki.css';
import '../../css/i/ip8mjmxtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t2zihunpi"/><path class="nuiom3xgn"/><path class="u07xh6bzl"/><path class="ra5mw5bki"/><path class="ip8mjmxtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sabnzbd" {...props}></Icon>
