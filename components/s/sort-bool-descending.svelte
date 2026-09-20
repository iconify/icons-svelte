<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhdbi7b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhdbi7b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-bool-descending" {...props}></Icon>
