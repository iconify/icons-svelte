<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/favsqtb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="favsqtb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:syncloud-dark" {...props}></Icon>
