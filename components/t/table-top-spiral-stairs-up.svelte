<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olo5y3b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="olo5y3b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-spiral-stairs-up" {...props}></Icon>
