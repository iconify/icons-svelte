<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5lejhb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p5lejhb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:square-grid-circle-stroke-20" {...props}></Icon>
