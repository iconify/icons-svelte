<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe5x2sqyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="xe5x2sqyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-door-one-way-up" {...props}></Icon>
