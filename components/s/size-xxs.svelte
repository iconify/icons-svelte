<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p22l6fwcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p22l6fwcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-xxs" {...props}></Icon>
