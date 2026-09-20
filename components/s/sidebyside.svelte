<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwqnu5bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rwqnu5bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:sidebyside" {...props}></Icon>
