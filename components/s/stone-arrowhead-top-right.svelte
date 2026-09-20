<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc8nh-b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oc8nh-b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-arrowhead-top-right" {...props}></Icon>
