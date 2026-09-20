<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_9h3draw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z_9h3draw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:up" {...props}></Icon>
