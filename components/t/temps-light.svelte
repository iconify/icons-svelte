<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph7np0z8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ph7np0z8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temps-light" {...props}></Icon>
