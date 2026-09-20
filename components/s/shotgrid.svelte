<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy3gjdo1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cy3gjdo1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:shotgrid" {...props}></Icon>
