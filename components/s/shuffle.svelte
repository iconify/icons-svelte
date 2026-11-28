<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jso2fwbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jso2fwbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shuffle" {...props}></Icon>
