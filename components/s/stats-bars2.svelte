<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7qhb_-hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g7qhb_-hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:stats-bars2" {...props}></Icon>
