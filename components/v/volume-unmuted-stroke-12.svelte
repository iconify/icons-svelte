<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4hgy2b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n4hgy2b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-unmuted-stroke-12" {...props}></Icon>
