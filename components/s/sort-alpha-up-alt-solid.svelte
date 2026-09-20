<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6p4u8bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6p4u8bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-alpha-up-alt-solid" {...props}></Icon>
