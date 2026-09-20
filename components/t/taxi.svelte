<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ppv4bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e3ppv4bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:taxi" {...props}></Icon>
