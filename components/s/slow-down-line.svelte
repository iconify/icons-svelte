<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2dzy5b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2dzy5b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slow-down-line" {...props}></Icon>
