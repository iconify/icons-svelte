<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-x3gjg4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y-x3gjg4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:text-label" {...props}></Icon>
