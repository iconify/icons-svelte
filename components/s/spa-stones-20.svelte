<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts6bgccjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ts6bgccjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spa-stones-20" {...props}></Icon>
