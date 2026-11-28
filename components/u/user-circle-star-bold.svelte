<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u35k7d0yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u35k7d0yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-circle-star-bold" {...props}></Icon>
