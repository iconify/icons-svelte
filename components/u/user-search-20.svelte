<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd353pbda.css';
import '../../css/a/ad6ngxjuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sd353pbda"/><path class="ad6ngxjuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-search-20" {...props}></Icon>
