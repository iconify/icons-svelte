<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f687inzts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":659};
const content = `<path class="f687inzts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:twitter" {...props}></Icon>
