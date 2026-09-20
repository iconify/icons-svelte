<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1onwk--p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u1onwk--p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:spinner-third" {...props}></Icon>
