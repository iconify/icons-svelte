<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3fh5btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri3fh5btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sogo-dark" {...props}></Icon>
