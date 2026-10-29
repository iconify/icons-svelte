<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ibpnj1b4u.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/a/awi56bc7v.css';
import '../../css/x/x79el81bg.css';
import '../../css/w/w5sdavbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ibpnj1b4u wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="awi56bc7v wm-k"/><path class="wm-a x79el81bg"/><path class="w5sdavbab wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:water-balloon-blueprint" {...props}></Icon>
