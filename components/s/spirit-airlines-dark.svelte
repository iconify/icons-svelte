<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp3jjevwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp3jjevwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spirit-airlines-dark" {...props}></Icon>
