<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_5bvnb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s_5bvnb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:tags-thin" {...props}></Icon>
