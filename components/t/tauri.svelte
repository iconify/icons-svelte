<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqpi-g-5k.css';
import '../../css/p/pbrz3mfxd.css';
import '../../css/d/dtr438hsl.css';
import '../../css/m/m1uqg3ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":289};
const content = `<path class="uqpi-g-5k"/><circle transform="rotate(180 104.91 183.505)" class="pbrz3mfxd"/><path class="dtr438hsl"/><path class="m1uqg3ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tauri" {...props}></Icon>
