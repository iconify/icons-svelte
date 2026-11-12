<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isf22b0cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isf22b0cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tpdb-dark" {...props}></Icon>
