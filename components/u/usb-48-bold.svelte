<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylaicorwm.css';
import '../../css/s/su7a0euxn.css';
import '../../css/n/np4ropmkg.css';
import '../../css/b/bg3wu7bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ylaicorwm"/><path class="su7a0euxn"/><path class="np4ropmkg"/><path class="bg3wu7bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:usb-48-bold" {...props}></Icon>
