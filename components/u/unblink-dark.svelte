<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-qag6b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-qag6b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unblink-dark" {...props}></Icon>
