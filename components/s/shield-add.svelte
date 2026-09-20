<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znxifc1ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znxifc1ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-add" {...props}></Icon>
