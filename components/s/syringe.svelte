<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2p7kgczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="r2p7kgczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:syringe" {...props}></Icon>
