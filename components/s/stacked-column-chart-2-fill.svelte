<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fie42-j_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fie42-j_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:stacked-column-chart-2-fill" {...props}></Icon>
