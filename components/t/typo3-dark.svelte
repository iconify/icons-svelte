<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk15ehbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kk15ehbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typo3-dark" {...props}></Icon>
