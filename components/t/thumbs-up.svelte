<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugcfebgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gugcfebgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:thumbs-up" {...props}></Icon>
