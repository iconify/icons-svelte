<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omju9dpqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="omju9dpqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:text-width" {...props}></Icon>
