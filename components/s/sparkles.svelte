<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thi0yobpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thi0yobpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sparkles" {...props}></Icon>
