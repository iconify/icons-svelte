<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczd56bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tczd56bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-door-one-way-down" {...props}></Icon>
