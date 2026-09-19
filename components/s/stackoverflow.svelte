<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_g6_lbbk.css';
import '../../css/g/guoy00ruz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s_g6_lbbk"/><path class="guoy00ruz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackoverflow" {...props}></Icon>
