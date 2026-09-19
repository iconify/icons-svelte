<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9kairbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":384};
const content = `<path class="c9kairbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:undo" {...props}></Icon>
