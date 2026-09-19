<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pllr1xbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pllr1xbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:xt2-camera" {...props}></Icon>
