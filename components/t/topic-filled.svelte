<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q87b2fv6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q87b2fv6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:topic-filled" {...props}></Icon>
