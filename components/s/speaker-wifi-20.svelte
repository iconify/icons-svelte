<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_fvll7vg.css';
import '../../css/m/mdlomob-h.css';
import '../../css/w/w4rg-tzhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_fvll7vg"/><path class="mdlomob-h"/><path class="w4rg-tzhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-wifi-20" {...props}></Icon>
