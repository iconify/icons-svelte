<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nes2ifbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nes2ifbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:users" {...props}></Icon>
