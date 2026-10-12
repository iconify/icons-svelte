<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaqgxrbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xaqgxrbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-20" {...props}></Icon>
