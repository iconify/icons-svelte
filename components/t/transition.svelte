<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4guh2bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4guh2bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transition" {...props}></Icon>
