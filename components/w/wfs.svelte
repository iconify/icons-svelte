<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcdx0-dnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mcdx0-dnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:wfs" {...props}></Icon>
