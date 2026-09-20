<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knu3qfbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="knu3qfbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:volume-down-solid" {...props}></Icon>
