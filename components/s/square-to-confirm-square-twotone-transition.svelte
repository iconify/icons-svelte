<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/y/y591zt.css';
import '../../css/k/kofr8g.css';
import '../../css/f/fill-from-0.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew y591zt"/><path class="iw1iew kofr8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:square-to-confirm-square-twotone-transition" {...props}></Icon>
