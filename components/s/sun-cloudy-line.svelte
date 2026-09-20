<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoe905xwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoe905xwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sun-cloudy-line" {...props}></Icon>
