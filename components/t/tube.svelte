<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1vn95naj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1vn95naj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tube" {...props}></Icon>
