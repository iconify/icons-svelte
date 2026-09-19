<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlmv-7cof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xlmv-7cof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-muted-stroke-12" {...props}></Icon>
