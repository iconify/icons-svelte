<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4wh8ccuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x4wh8ccuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:utility-pole" {...props}></Icon>
