<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bse-bsrnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bse-bsrnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tv-outline" {...props}></Icon>
