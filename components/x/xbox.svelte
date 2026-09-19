<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncrn1j3qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ncrn1j3qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:xbox" {...props}></Icon>
