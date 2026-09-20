<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfhn1dbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfhn1dbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screw-flat-top" {...props}></Icon>
