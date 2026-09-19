<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szy1_ul7k.css';
import '../../css/f/fgrg7ftet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="szy1_ul7k"/><path class="fgrg7ftet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:signpost-stroke-12" {...props}></Icon>
