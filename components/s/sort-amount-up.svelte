<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cni9eacnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cni9eacnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-amount-up" {...props}></Icon>
