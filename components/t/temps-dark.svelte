<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntdd5ebmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntdd5ebmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temps-dark" {...props}></Icon>
