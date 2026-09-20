<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3y6igytu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r3y6igytu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:superpowers" {...props}></Icon>
