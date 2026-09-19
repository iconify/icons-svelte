<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw8x78bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qw8x78bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:wcs" {...props}></Icon>
