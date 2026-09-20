<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tblh_accd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tblh_accd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-circle-rectangle-filled" {...props}></Icon>
