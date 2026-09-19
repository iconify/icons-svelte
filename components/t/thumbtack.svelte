<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0tnvacgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y0tnvacgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thumbtack" {...props}></Icon>
