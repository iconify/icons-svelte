<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf0nombmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sf0nombmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:terramate" {...props}></Icon>
