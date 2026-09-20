<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh1_5c8zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh1_5c8zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-down-line" {...props}></Icon>
