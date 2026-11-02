<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf0pmjbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gf0pmjbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:splash-up-from-water" {...props}></Icon>
