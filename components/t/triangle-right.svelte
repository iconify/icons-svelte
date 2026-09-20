<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbrcyl_dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="cbrcyl_dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-right" {...props}></Icon>
