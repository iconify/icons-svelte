<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaw_zbcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gaw_zbcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:text-style-remix" {...props}></Icon>
