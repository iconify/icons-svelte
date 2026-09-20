<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihj02mbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihj02mbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telegram-light" {...props}></Icon>
