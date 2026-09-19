<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2djj2bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="z2djj2bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:swap-vertical-circle" {...props}></Icon>
