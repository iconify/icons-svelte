<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuj9c8f4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuj9c8f4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stack-overflow" {...props}></Icon>
