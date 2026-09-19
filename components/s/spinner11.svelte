<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_0get0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n4_0get0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner11" {...props}></Icon>
