<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbh3g-16i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbh3g-16i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:signpost-l-1" {...props}></Icon>
