<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7b8aob9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r7b8aob9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:user" {...props}></Icon>
