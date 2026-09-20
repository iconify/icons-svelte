<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pace_-bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pace_-bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:trend-static" {...props}></Icon>
