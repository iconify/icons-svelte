<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8bl1_b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8bl1_b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:symbolab" {...props}></Icon>
