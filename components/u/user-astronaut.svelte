<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m265btblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m265btblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-astronaut" {...props}></Icon>
