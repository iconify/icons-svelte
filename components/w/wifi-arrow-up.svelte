<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav0ifzme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jav0ifzme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-arrow-up" {...props}></Icon>
