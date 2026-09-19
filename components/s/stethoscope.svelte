<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yggif9bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yggif9bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:stethoscope" {...props}></Icon>
