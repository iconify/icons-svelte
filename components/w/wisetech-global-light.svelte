<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rspr33bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1534};
const content = `<path class="rspr33bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wisetech-global-light" {...props}></Icon>
