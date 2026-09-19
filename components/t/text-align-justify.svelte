<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qogk-zxfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qogk-zxfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:text-align-justify" {...props}></Icon>
