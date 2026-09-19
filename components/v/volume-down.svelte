<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7o-o3clb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1280};
const content = `<path class="i7o-o3clb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:volume-down" {...props}></Icon>
