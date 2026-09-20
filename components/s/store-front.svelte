<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-699-bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r-699-bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:store-front" {...props}></Icon>
