<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6u_pab5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b6u_pab5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:x" {...props}></Icon>
