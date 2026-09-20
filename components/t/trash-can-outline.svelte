<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np9o9uu-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np9o9uu-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trash-can-outline" {...props}></Icon>
