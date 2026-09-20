<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofp7wzg4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ofp7wzg4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stop-solid" {...props}></Icon>
