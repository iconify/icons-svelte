<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drgua2bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="drgua2bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:swipe-map-h" {...props}></Icon>
