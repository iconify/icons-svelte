<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7uhpm4sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="w7uhpm4sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:world-folder" {...props}></Icon>
