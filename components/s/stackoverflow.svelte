<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0fd6ob0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="p0fd6ob0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:stackoverflow" {...props}></Icon>
