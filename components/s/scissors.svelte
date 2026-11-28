<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrhzudmjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrhzudmjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:scissors" {...props}></Icon>
