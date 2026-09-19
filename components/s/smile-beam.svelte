<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuz9bmb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="yuz9bmb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:smile-beam" {...props}></Icon>
