<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpne1_b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fpne1_b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:sort-ascending" {...props}></Icon>
