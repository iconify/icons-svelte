<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wionk-b8u.css';
import '../../css/n/n_arg_b-v.css';
import '../../css/r/r2rl9cbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGcJptGk5B" x1="0" x2="512" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="wionk-b8u"/><stop offset="1" class="n_arg_b-v"/></linearGradient><path fill="url(#SVGcJptGk5B)" class="r2rl9cbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wastebin" {...props}></Icon>
