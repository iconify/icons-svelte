<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-a5-2npd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-a5-2npd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:th-large" {...props}></Icon>
