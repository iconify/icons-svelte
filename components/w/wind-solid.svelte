<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxjspdb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kxjspdb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wind-solid" {...props}></Icon>
