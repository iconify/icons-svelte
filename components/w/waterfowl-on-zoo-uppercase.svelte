<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5tkqbcgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z5tkqbcgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:waterfowl-on-zoo-uppercase" {...props}></Icon>
