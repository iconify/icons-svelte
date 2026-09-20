<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rftvm9l3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rftvm9l3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-rotate-counterclockwise" {...props}></Icon>
