<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czalfpt_j.css';
import '../../css/g/g1zbydbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czalfpt_j"/><path class="g1zbydbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-up-20" {...props}></Icon>
