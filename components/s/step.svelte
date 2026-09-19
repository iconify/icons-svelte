<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x65shebem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x65shebem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:step" {...props}></Icon>
