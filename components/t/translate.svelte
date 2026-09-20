<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hunh2paym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hunh2paym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:translate" {...props}></Icon>
