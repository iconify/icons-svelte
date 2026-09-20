<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_6laqwbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_6laqwbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:up-square-o" {...props}></Icon>
