<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3x4b222t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3x4b222t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustfs" {...props}></Icon>
