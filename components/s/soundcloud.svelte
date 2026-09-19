<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwrzs0fwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fwrzs0fwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:soundcloud" {...props}></Icon>
