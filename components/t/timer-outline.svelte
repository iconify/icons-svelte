<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzif5jboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzif5jboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-outline" {...props}></Icon>
