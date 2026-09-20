<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzui9exaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kzui9exaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:search" {...props}></Icon>
