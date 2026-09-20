<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st9o-6h2k.css';
import '../../css/l/lgnrw_bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="st9o-6h2k"/><path class="lgnrw_bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:up-down-black-arrow" {...props}></Icon>
