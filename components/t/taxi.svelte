<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5q0w7gwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5q0w7gwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:taxi" {...props}></Icon>
