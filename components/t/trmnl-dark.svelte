<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epncsdd1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epncsdd1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trmnl-dark" {...props}></Icon>
