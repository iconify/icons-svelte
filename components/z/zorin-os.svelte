<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-8ww2bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-8ww2bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zorin-os" {...props}></Icon>
