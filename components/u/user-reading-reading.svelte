<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3hy0rjyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3hy0rjyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-reading-reading" {...props}></Icon>
