<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1hgjccdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1hgjccdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikipedia-light" {...props}></Icon>
