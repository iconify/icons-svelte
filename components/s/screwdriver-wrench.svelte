<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmlkhtbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmlkhtbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:screwdriver-wrench" {...props}></Icon>
