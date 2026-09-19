<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll6-iwbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ll6-iwbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:viewfinder-circle-20-solid" {...props}></Icon>
