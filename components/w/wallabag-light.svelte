<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzq9j2bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzq9j2bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wallabag-light" {...props}></Icon>
