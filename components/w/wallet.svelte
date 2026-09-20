<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_w_2b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jn_w_2b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:wallet" {...props}></Icon>
