<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foizl_b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="foizl_b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:search-heart-fill" {...props}></Icon>
