<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3w_wnbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c3w_wnbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-solid" {...props}></Icon>
