<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnv09c1ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pnv09c1ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-right-16" {...props}></Icon>
