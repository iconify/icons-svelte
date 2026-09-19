<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfncn9b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":16};
const content = `<path class="jfncn9b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:stepback" {...props}></Icon>
