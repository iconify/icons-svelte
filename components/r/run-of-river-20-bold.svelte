<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_i3djllq.css';
import '../../css/p/p8remmbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_i3djllq"/><path class="p8remmbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:run-of-river-20-bold" {...props}></Icon>
