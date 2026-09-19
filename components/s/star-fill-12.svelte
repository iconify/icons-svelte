<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk0rmxbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lk0rmxbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:star-fill-12" {...props}></Icon>
