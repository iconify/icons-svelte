<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn27sub2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rn27sub2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:star-stroke-12" {...props}></Icon>
