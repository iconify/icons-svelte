<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_z22dla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gf_z22dla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spell-check" {...props}></Icon>
