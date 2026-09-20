<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg7c7ibcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg7c7ibcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seed-off-outline" {...props}></Icon>
