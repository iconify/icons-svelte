<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osua4ybwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="osua4ybwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:safe" {...props}></Icon>
