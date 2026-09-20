<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjf5vubbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tjf5vubbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tag" {...props}></Icon>
