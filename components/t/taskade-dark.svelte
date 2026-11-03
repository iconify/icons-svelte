<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a52e49pvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a52e49pvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taskade-dark" {...props}></Icon>
