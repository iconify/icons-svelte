<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-__ckyep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h-__ckyep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:smiley" {...props}></Icon>
