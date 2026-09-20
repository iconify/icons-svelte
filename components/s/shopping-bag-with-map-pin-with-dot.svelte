<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km-1_cczy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="km-1_cczy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-map-pin-with-dot" {...props}></Icon>
