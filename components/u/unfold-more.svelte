<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cazqnib9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":384};
const content = `<path class="cazqnib9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:unfold-more" {...props}></Icon>
