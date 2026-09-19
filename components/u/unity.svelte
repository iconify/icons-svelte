<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb52r_b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hb52r_b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:unity" {...props}></Icon>
