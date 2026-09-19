<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnw1cjxky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jnw1cjxky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:stacked-column-chart-2" {...props}></Icon>
