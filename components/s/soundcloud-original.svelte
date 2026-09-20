<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxo1zg92k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vxo1zg92k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:soundcloud-original" {...props}></Icon>
