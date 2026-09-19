<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vic4fznwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vic4fznwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:temperature-high" {...props}></Icon>
