<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4fasjb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h4fasjb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:size" {...props}></Icon>
