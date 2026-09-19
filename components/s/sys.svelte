<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ve0x4ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e8ve0x4ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sys" {...props}></Icon>
