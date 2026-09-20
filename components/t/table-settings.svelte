<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cias1zbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cias1zbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-settings" {...props}></Icon>
