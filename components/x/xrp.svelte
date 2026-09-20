<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-1pznex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-1pznex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:xrp" {...props}></Icon>
