<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckp9ovbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckp9ovbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typetype" {...props}></Icon>
