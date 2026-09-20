<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu3pwt-uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3pwt-uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shape-square-plus" {...props}></Icon>
