<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6641zwgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6641zwgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-refresh" {...props}></Icon>
