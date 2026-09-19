<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ht4_blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="u9ht4_blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:skull-crossbones" {...props}></Icon>
