<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0k7v5bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h0k7v5bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:zoom-out" {...props}></Icon>
