<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ris3ovb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ris3ovb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:special-character" {...props}></Icon>
