<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nocj3nbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nocj3nbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:unlock" {...props}></Icon>
