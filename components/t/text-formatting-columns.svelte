<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8hp-10jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d8hp-10jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-columns" {...props}></Icon>
