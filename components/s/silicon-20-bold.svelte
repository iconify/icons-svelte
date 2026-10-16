<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpwlrrj0w.css';
import '../../css/v/vc4rurisx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpwlrrj0w"/><path class="vc4rurisx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silicon-20-bold" {...props}></Icon>
