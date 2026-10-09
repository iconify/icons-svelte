<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs4tj7b-n.css';
import '../../css/r/rn3p8rbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hs4tj7b-n"/><path class="rn3p8rbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-2-20-bold" {...props}></Icon>
