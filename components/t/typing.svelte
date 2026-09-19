<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv6imwvyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zv6imwvyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:typing" {...props}></Icon>
