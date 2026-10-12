<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt-d5tt_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt-d5tt_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-stroke-20" {...props}></Icon>
