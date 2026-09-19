<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i47cngb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i47cngb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type" {...props}></Icon>
