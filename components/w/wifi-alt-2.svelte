<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pccm1gbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":400};
const content = `<path class="pccm1gbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wifi-alt-2" {...props}></Icon>
