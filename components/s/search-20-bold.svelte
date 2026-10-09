<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj3zoshwv.css';
import '../../css/u/uf825eo1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jj3zoshwv"/><path class="uf825eo1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-20-bold" {...props}></Icon>
