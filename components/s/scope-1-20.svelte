<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcck3kbsm.css';
import '../../css/r/riwxhe31h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zcck3kbsm"/><path class="riwxhe31h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scope-1-20" {...props}></Icon>
