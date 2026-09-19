<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9aw0ccuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9aw0ccuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:snow" {...props}></Icon>
