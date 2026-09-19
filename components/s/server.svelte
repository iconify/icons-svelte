<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f03viiyfk.css';
import '../../css/u/ux3cgkxqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f03viiyfk"/><path class="ux3cgkxqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:server" {...props}></Icon>
