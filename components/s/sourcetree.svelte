<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hctv6-d5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hctv6-d5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:sourcetree" {...props}></Icon>
