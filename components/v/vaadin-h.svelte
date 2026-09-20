<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ts60vxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l6ts60vxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:vaadin-h" {...props}></Icon>
