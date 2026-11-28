<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvd48gpsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cvd48gpsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:steak" {...props}></Icon>
