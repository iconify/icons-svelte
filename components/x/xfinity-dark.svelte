<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu8psr46c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu8psr46c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xfinity-dark" {...props}></Icon>
