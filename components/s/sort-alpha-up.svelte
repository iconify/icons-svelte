<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye7an4k6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ye7an4k6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-alpha-up" {...props}></Icon>
