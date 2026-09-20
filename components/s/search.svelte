<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1h9apblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z1h9apblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:search" {...props}></Icon>
