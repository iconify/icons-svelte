<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiy-tl0rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yiy-tl0rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:three-dots-vertical" {...props}></Icon>
