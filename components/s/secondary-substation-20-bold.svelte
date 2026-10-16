<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnex-cbcf.css';
import '../../css/m/m480pab_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pnex-cbcf"/><path class="m480pab_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:secondary-substation-20-bold" {...props}></Icon>
