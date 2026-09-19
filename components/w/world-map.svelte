<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agt8pubkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="agt8pubkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:world-map" {...props}></Icon>
