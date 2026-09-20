<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwnwoqbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lwnwoqbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-header-image" {...props}></Icon>
