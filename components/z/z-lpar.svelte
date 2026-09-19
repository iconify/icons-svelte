<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0x1nqbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s0x1nqbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:z-lpar" {...props}></Icon>
