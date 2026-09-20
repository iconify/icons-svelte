<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q126ik-do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q126ik-do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wifi3" {...props}></Icon>
