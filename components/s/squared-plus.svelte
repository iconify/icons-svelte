<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tly8mhaex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tly8mhaex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:squared-plus" {...props}></Icon>
