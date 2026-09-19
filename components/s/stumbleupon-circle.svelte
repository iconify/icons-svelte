<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_wgz9s9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="l_wgz9s9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stumbleupon-circle" {...props}></Icon>
