<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sctufhdka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sctufhdka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:users-1-bold" {...props}></Icon>
