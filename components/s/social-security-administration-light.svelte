<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ei1uv_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2ei1uv_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:social-security-administration-light" {...props}></Icon>
