<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vutc8zb9c.css';
import '../../css/e/el0rrrluf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vutc8zb9c"/><path class="el0rrrluf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:user-star" {...props}></Icon>
